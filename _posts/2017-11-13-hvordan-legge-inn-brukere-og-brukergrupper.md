---
ID: 267
post_title: Administrere brukere
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=267
published: true
post_date: 2017-11-13 10:28:21
---
For å kunne oppdatere og endre informasjon om brukere og brukergrupper, så må du være systemadministrator eller superbruker.
<h2>Bruker</h2>
&nbsp;

Administrator kan opprette ny bruker eller endre opplysninger om eksisterende brukere ved menyvalg:
<strong>ADMINISTRASJON =&gt; ADMIN =&gt; ADMINISTRERE BRUKERE</strong>

Skjermbildet ser da slik ut:
![administrere brukere](http://manual.aktiv-kommune.no/wp-content/uploads/2018/02/brukereogbrukergrupper.png)

Her kan du vise, endre eller gjøre eksisterende bruker inaktiv. Når en saksbehandler eller superbruker ikke lenger skal ha tilgang anbefales det å gjøre brukeren inaktiv heller enn å slette den for å beholde historikk om saksbehandlingen.

For å legge til ny bruker klikker du på
![legg til](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/leggtil.png)

Følgende skjermbilde dukker opp:
![Ny-bruker-skjermbilde](http://manual.aktiv-kommune.no/wp-content/uploads/2017/11/Ny-bruker-skjermbilde.png)

Under arkfanen *Brukerdata* fyller du ut informasjonen om brukeren:

**Feltnavn**| Om feltet/ Aksjon (hva skal gjøres)
--------------------------|---------------------------------------------
**Brukernavn:**

&nbsp;

&nbsp;

&nbsp;

|Brukernavnet som brukeren logger seg inn med. Vi anbefaler at organisasjoner og privatpersoner bruker sin e-postadresse som brukernavn. For saksbehandlere og superbrukere vil det være en fordel å bruke brukerident (id) som brukes til pålogging på kommunens nett. På sikt vil det bli enklere å bruke Singel Sign-On (SSO) for de kommuner som ønsker det. Bergen kommune har SSO-pålogging for sine saksbehandlere.
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
&gt; *Saksbehandler* må ha hake ved *Admin* for applikasjonen (modulen) *Booking*

Når du har fylt inn den informasjonen som skal inn, klikker du på
![lagre2](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre2.png)

Brukeren er da lagt til, og du må klikke på *Avbryt* for å komme ut av skjermbildet.

## Begrenset tilgang til Aktiv kommune
Roller i Aktiv kommune:
**Administrator – Tilgang til å opprette nytt og endre
**Saksbehandler – Kun tilgang til å endre

Saksbehandlere kan opprette nye organisasjoner, sende epost, håndtere søknader og rapportere. For at en saksbehandler skal kunne administrere bygg, sesonger, ukeplaner, faktura osv må det gis utvidet rettighet. Under <strong>BYGG / ANLEGG =&gt; RESSURSER OG SESONGER =&gt; RETTIGHETER </strong>gis de enkelte brukerne rettigheter til å redigere ulike bygg, ressurser og sesonger.

## Inaktivering av bruker

Brukere skal ikke slettes fra systemet, men settes som <em>inaktiv</em> om de ikke lengre skal ha tilgang til systemet. For å gjøre dette velger du:

<strong>ADMINISTRASJON =&gt; ADMIN =&gt; ADMINISTRERE BRUKERE</strong>

Så klikker du på *Rediger* for den aktuelle brukeren. På det nye skjermbildet haker du vekk for *Bruker er aktiv* og klikker på
![lagre2](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre2.png)

Brukeren er da inaktiv og har ikke lengre tilgang til systemet. Brukeren kan gjøres aktiv igjen om det blir aktuelt, for eksempel etter endt permisjon.

## Brukergrupper

NB! I stedet for å gi enkelttilganger til en konkret (ny) bruker under *Applikasjoner*, så er klart beste praksis at tilgang gis ved at bruker blir meldt inn i en brukergruppe (enten som saksbehandler, superbruker eller systemadministrator). Dette skjer via kommandoen:

<strong>ADMINISTRASJON =&gt; ADMIN =&gt; ADMINISTRERE GRUPPER.</strong>

Neste steg vil være [å opprette en kommune eller bydeler/områder.](https://manual.aktiv-kommune.no/?p=291)