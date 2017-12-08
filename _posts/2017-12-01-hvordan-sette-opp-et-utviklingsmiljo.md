---
ID: 370
post_title: Hvordan sette opp et utviklingsmiljø?
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=370
published: true
post_date: 2017-12-01 09:39:15
---
Ønsker du å sette opp et utviklingsmiljø for AktivKommune tilpasset *Vargant* og *Netbeans* kan du lese mer [her](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/aktivkommune_oppsett_av_utviklingsmiljo.pdf).

## Setup Ubuntu server
~~~
sudo apt-get update
sudo apt-get install -y apt-utils
sudo apt-get install -y apache2
sudo apt-get install -y mysql-client-core-5.7
sudo apt-get install -y libapache2-mod-php7.0 php7.0 php7.0-curl php7.0-intl php7.0-mysql php-xdebug php-apcu php7.0-dev php7.0-xmlrpc php7.0-xsl php7.0-sybase php7.0-pgsql php7.0-json php7.0-gd php-imagick php7.0-imap php7.0-soap php7.0-zip php7.0-mbstring php-pear libaio1 locales
sudo apt-get install -y git
sudo apt-get install -y less vim-tiny
sudo apt-get install -y subversion
sudo apt-get install -y apg
sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt/ `lsb_release -cs`-pgdg main" >> /etc/apt/sources.list.d/pgdg.list'
wget -q https://www.postgresql.org/media/keys/ACCC4CF8.asc -O - | sudo apt-key add -
sudo apt-get update
sudo apt-get install -y postgresql postgresql-contrib
~~~

### Fix permissions
Fixing listen_addresses on postgresql.conf&quot;
~~~
    sudo sed -i "s/#listen_address.*/listen_addresses '*'/" /etc/postgresql/9.6/main/postgresql.conf
~~~

### Fixing postgres pg_hba.conf file
Replace the ipv4 host line with the above line
~~~
sudo cat >> /etc/postgresql/9.6/main/pg_hba.conf <<EOF
# Accept all IPv4 connections - FOR DEVELOPMENT ONLY!!!
host    all         all         0.0.0.0/0             md5
EOF
~~~

### Create Role and login
~~~
sudo su postgres -c 'psql -c "CREATE ROLE portico SUPERUSER LOGIN PASSWORD '"'"'portico'"'"'" '
sudo apt install -y whois
sudo useradd -p `mkpasswd "portico"` -d /home/"portico" -m -g users -s /bin/bash "portico"
sudo echo 'portico  ALL=(ALL:ALL) ALL' >> /etc/sudoers
~~~

sudo mkdir /var/www/html/portico
sudo chown portico.users /var/www/html/portico

sudo apt-get upgrade -y

sudo sed -i 's/"GP"/"GPCS"/' /etc/php/7.0/apache2/php.ini
sudo sed -i 's/"GP"/"GPCS"/' /etc/php/7.0/cli/php.ini

sudo cat > /etc/php/7.0/apache2/conf.d/91-app.ini <<EOF
xdebug.max_nesting_level=200
xdebug.overload_var_dump=Off
xdebug.remote_autostart=Off
xdebug.remote_connect_back=On
xdebug.remote_enable=On
xdebug.remote_port=9000
session.cookie_secure=Off
session.use_cookies=On
session.use_only_cookies=On
short_open_tag=Off
request_order = "GPCS"
variables_order = "GPCS"
memory_limit = 5048M
max_input_vars = 5000
error_reporting = E_ALL & ~E_NOTICE
display_errors = On
post_max_size = 20M
upload_max_filesize = 8M
EOF

sudo cp /etc/php/7.0/apache2/conf.d/91-app.ini /etc/php/7.0/cli/conf.d/91-app.ini

sudo service postgresql restart
sudo service apache2 restart
~~~~

## Backup av PostgreSQL database
~~~
pg_dump -U portico portico > portico_backup.sql
~~~

## Lage PostgreSQL database
~~~
sudo -u postgres createdb portico
~~~

## Restore PostgreSQL database
~~~
psql -U portico portico > portico_backup.sql
~~~