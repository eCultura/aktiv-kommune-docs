---
ID: 267
post_title: >
  Hvordan opprette/endre/inaktivere
  brukere og brukergrupper?
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=267
published: true
post_date: 2017-11-13 10:28:21
---
For å kunne oppdatere og endre informasjon om brukere og brukergrupper, så må du ha rettighetene som systemadministrator eller superbruker.


## Bruker

For å opprette ny bruker eller endre opplysninger om eksisterende brukere velger du kommandoen:
<strong>ADMINISTRASJON => ADMIN => ADMINISTRERE BRUKERE</strong> 

Skjermbildet ser da slik ut: 
![administrere brukere](http://manual.aktiv-kommune.no/wp-content/uploads/2018/02/brukereogbrukergrupper.png)

Her kan du vise, endre eller gjøre eksisterende bruker inaktiv. Når en saksbehandler eller superbruker slutter i kommunen, eller ikke lenger skal ha tilgang, så vil brukeren ikke slettes fra systemet, men kun gjøres inaktiv. Med dette grepet vil informasjon/historikk om saksbehandlingen beholdes.

For å legge til ny bruker klikker du på
![legg til](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/leggtil.png)

Følgende skjermbilde dukker opp:
![Ny-bruker-skjermbilde](http://manual.aktiv-kommune.no/wp-content/uploads/2017/11/Ny-bruker-skjermbilde.png)

Under arkfanen *Brukerdata* fyller du ut informasjonen om brukeren:

**Feltnavn**| Om feltet/ Aksjon (hva skal gjøres)
--------------------------|---------------------------------------------
**Brukernavn:** |Brukernavnet som brukeren logger seg inn med. Vi anbefaler at organisasjoner og privatpersoner bruker sin e-postadresse som brukernavn. For saksbehandlere og superbrukere vil det være en fordel å bruke brukerident (id) som brukes til pålogging på kommunens nett. På sikt vil det bli enklere å bruke Singel Sign-On (SSO) for de kommuner som ønsker det. Bergen kommune har SSO-pålogging for sine saksbehandlere.
**Fornavn:** |Fornavn på brukeren.
**Etternavn:** |Etternavn på brukeren.
**Passord:** |Passord brukerens skal bruke når han/hun logger inn på siden.
**Skriv inn passord igjen:** |Gjenta passord.
**Kontakt:**| (brukes ikke)
**Kan bytte passord:** |Hak vekk om bruker ikke selv skal kunne bytte passord.
**Anonym bruker (vises ikke i sesjonslisten):** |Hak av om bruker skal være anonym. 
**Utløpsdato:** |Når brukeren ikke lengre skal ha tilgang. Denne er satt til "aldri" som standard. 
**Kvote:** |Kvote for hvor store filer brukeren kan laste opp. 

Under arkfanen *Grupper* kan du hake av for hvilke grupper brukeren skal tilhøre. Minimum en gruppe bør velges.

Under arkfanen *Applikasjoner* gir du tilgang til moduler og definerer hvorvidt brukeren skal ha tilgang som bruker eller administrator. 
> *Saksbehandler* må ha hake ved *Admin* for applikasjonen (modulen) *Booking*

Når du har fylt inn den informasjonen som skal inn, klikker du på 
![lagre2](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre2.png)

Brukeren er da lagt til, og du må klikke på *Avbryt* for å komme ut av skjermbildet. 

## Inaktivering av bruker

Brukere skal ikke slettes fra systemet, men settes som <em>inaktiv</em> om de ikke lengre skal ha tilgang til systemet. For å gjøre dette velger du: 

<strong>ADMINISTRASJON => ADMIN => ADMINISTRERE BRUKERE</strong>

Så klikker du på *Rediger* for den aktuelle brukeren. På det nye skjermbildet haker du vekk for *Bruker er aktiv* og klikker på 
![lagre2](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre2.png)

Brukeren er da inaktiv og har ikke lengre tilgang til systemet. Brukeren kan gjøres aktiv igjen om det blir aktuelt, for eksempel etter endt permisjon.

## Brukergrupper

NB! I stedet for å gi enkelttilganger under *Applikasjoner*, så bør du som systemadministrator eller superbruker definere egne tilganger på gruppenivå under: 

<strong>ADMINISTRASJON => ADMIN => ADMINISTRERE GRUPPER.</strong>


Neste steg vil være [å opprette en kommune eller bydeler.](https://manual.aktiv-kommune.no/?p=291)