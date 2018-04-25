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
Administrator kan opprette ny bruker eller endre opplysninger om eksisterende brukere ved menyvalg:
<strong>ADMINISTRASJON =&gt; ADMIN =&gt; ADMINISTRERE BRUKERE</strong>

Skjermbildet ser da slik ut:
![administrere brukere](http://manual.aktiv-kommune.no/wp-content/uploads/2018/02/brukereogbrukergrupper.png)

Her kan du vise, endre eller gjøre eksisterende bruker inaktiv. Når en saksbehandler eller superbruker ikke lenger skal ha tilgang anbefales det å gjøre brukeren inaktiv heller enn å slette den for å beholde historikk om saksbehandlingen.

For å legge til ny bruker klikker du på
![legg til](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/leggtil.png)

Under arkfanen *Brukerdata* fyller du ut informasjonen om brukeren:

**Feltnavn**| Hva fylles ut
--------------------------|---------------------------------------------
**Brukernavn:**|Organisasjoner og privatpersoner anbefales å bruke sin e-postadresse som brukernavn. Saksbehandlere og superbrukere anbefales å bruke sin brukerID som brukes til pålogging på kommunens nett.
**Fornavn:** |Fornavn på brukeren.
**Etternavn:** |Etternavn på brukeren.
**Passord:** |Passord brukeren skal bruke ved innlogging på siden
**Skriv inn passord igjen:** |Gjenta passord.
**Kontakt:**| (brukes ikke)
**Kan bytte passord:** |Fjern haken dersom bruker ikke selv skal kunne bytte passord
**Anonym bruker (vises ikke i sesjonslisten):** |Hak av om bruker skal være anonym
**Utløpsdato:** |Når brukeren ikke lengre skal ha tilgang. Denne er satt til "aldri" som standard.
**Kvote:** |Kvote for hvor store filer brukeren kan laste opp.

Under arkfanen *Grupper* kan du hake av for hvilke grupper brukeren skal tilhøre. Minimum en gruppe bør velges.

Under arkfanen *Applikasjoner* gir du tilgang til moduler og definerer hvorvidt brukeren skal ha tilgang som bruker eller administrator.
> Arkfanen "Applikasjoner" trenger normalt ikke brukes så lenge brukeren er tilknyttet minst en brukergruppe under arkfanen "Grupper"  
Når du har fylt inn den informasjonen som skal inn, klikker du på
![lagre2](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre2.png)

Brukeren er da lagt til, og du må klikke på *Avbryt* for å komme ut av skjermbildet.

## Begrenset tilgang til Aktivkommune
De tre rollene Saksbehandler, Superbruker og Systemadministrator i Aktivkommune har med noen unntak følgende rettigheter:
**Systemadministrator og Superbruker – Tilgang til å opprette nye, deaktivere/slette og endre elementer i Aktivkommune
**Saksbehandler – Normalt kun tilgang til å endre på elementer i Aktivkommune.
Eksempel på elementer er; områder, bydeler, eiendommer, bygg, ressursgrupper, ressurser

Saksbehandlere kan opprette nye organisasjoner, sende epost, håndtere søknader og rapportere. For at en saksbehandler skal kunne administrere bygg, sesonger, ukeplaner, faktura osv må det gis utvidet rettighet (fortrinnsvis som "Superbruker" eller unntaksvis som "Systemadministrator"). Under <strong>BYGG / ANLEGG =&gt; RESSURSER OG SESONGER =&gt; RETTIGHETER </strong>gis de enkelte brukerne rettigheter til å redigere ulike bygg, ressurser og sesonger.

## Inaktivering av bruker

Brukere skal ikke slettes fra systemet, men settes som <em>inaktiv</em> om de ikke lengre skal ha tilgang til systemet. For å gjøre dette velger du:

<strong>ADMINISTRASJON =&gt; ADMIN =&gt; ADMINISTRERE BRUKERE</strong>

Så klikker du på *Rediger* for den aktuelle brukeren. På det nye skjermbildet haker du vekk for *Bruker er aktiv* og klikker på
![lagre2](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre2.png)

Brukeren er da inaktiv og har ikke lengre tilgang til systemet. Brukeren kan gjøres aktiv igjen om det blir aktuelt, for eksempel etter endt permisjon.

## Brukergrupper

NB! I stedet for å gi enkelttilganger til en ny bruker under *Applikasjoner* anbefales det å gi tilgang ved at bruker blir meldt inn i en brukergruppe (saksbehandler, superbruker eller systemadministrator). Dette skjer via kommandoen:

<strong>ADMINISTRASJON =&gt; ADMIN =&gt; ADMINISTRERE GRUPPER.</strong>

Neste steg vil være [å opprette en kommune eller bydeler/områder.](https://manual.aktiv-kommune.no/?p=291)