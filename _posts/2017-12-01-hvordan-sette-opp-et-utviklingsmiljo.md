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
Ønsker du å sette opp et utviklingsmiljø for AktivKommune kan du lese mer [her](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/aktivkommune_oppsett_av_utviklingsmiljo.pdf).

## Backup av PostgreSQL database
~~~
pg_dump -U portico portico &gt; portico_backup.sql
~~~

## Lage PostgreSQL database
~~~
sudo -u postgres createdb portico
~~~

## Restore PostgreSQL database
~~~
psql -U portico portico &lt; portico_backup.sql
~~~