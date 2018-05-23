---
ID: 267
post_title: >
  Opprette og administrere brukertilganger
  i systemet
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=267
published: true
post_date: 2017-11-13 10:28:21
---
For å kunne opprette, oppdatere og endre informasjon om brukere og brukergrupper, så må du ha tilgang som systemadministrator eller superbruker.

<h2>Opprette og endre på bruker</h2>
Administrator kan opprette ny bruker eller endre opplysninger om eksisterende brukere ved menyvalg:
<strong>ADMINISTRASJON =&gt; ADMIN =&gt; ADMINISTRERE BRUKERE</strong>

Skjermbildet ser da slik ut:
![administrere brukere](http://manual.aktiv-kommune.no/wp-content/uploads/2018/02/brukereogbrukergrupper.png)

Her kan du vise, endre eller gjøre eksisterende bruker inaktiv. Når en saksbehandler eller superbruker ikke lenger skal ha tilgang til systemet, så anbefales det å gjøre brukeren inaktiv heller enn å slette brukeren. Da vil man kunne beholde historikk om saksbehandlingen.

For å legge til ny bruker klikker du på
![legg til](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/leggtil.png)

Under arkfanen *Brukerdata* fyller du ut informasjonen om brukeren:

**Feltnavn**| Hva fylles ut
--------------------------|---------------------------------------------
**Brukernavn:**|Organisasjoner og privatpersoner anbefales å bruke sin e-postadresse som brukernavn. For saksbehandlere og superbrukere (ansatte i kommunen) anbefales det at disse får tildelt som kommunale bruker-ID også som brukernavn. Det er mulig å knytte Singel Sign On (SSO) på løsningen for de kommuner som har dette.
**Fornavn:** |Fornavn på brukeren.
**Etternavn:** |Etternavn på brukeren.
**Passord:** |Passord brukeren skal bruke ved innlogging på siden.
**Skriv inn passord igjen:** |Gjenta passord.
**Kontakt:**| (brukes ikke)
**Kan bytte passord:** |Fjern haken dersom bruker ikke selv skal kunne bytte passord
**Anonym bruker (vises ikke i sesjonslisten):** |Hak av om bruker skal være anonym
**Utløpsdato:** |Når brukeren ikke lengre skal ha tilgang. Denne er satt til "aldri" som standard.
**Kvote:** |Kvote for hvor store filer brukeren kan laste opp.

> Det er mulig å forandre kravene til passordstyrke (passordregler). Systemet leveres med normalt god passordstyrke. Endringer gjøres i SETUP-delen av systemet, og det er driftsoperatør av Aktivkommune som bør gjøre endringene.

Under arkfanen *Grupper* kan du hake av for hvilke grupper brukeren skal tilhøre. Minimum en gruppe må velges.

Under arkfanen *Applikasjoner* gir du tilgang til moduler og definerer hvorvidt brukeren skal ha tilgang som bruker eller administrator.
> Arkfanen "Applikasjoner" trenger normalt ikke brukes så lenge brukeren er tilknyttet minst en brukergruppe under arkfanen "Grupper"

Når du har fylt inn den informasjonen som skal inn, klikker du på
![lagre2](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre2.png)

Brukeren er da lagt til, og du må klikke på *Avbryt* for å komme ut av skjermbildet.

## Begrenset tilgang til Aktivkommune
De tre rollene Saksbehandler, Superbruker og Systemadministrator i Aktivkommune har med noen unntak følgende rettigheter:
* Systemadministrator og Superbruker – Tilgang til å opprette nye, deaktivere/slette og alle typer elementer i Aktivkommune
* Saksbehandler – Normalt kun tilgang til å endre på bookingelementer i Aktivkommune.

>Eksempel på elementer er; områder, bydeler, eiendommer, bygg, ressursgrupper, utleieobjekter (ressurser), organisasjoner

>Eksempel på bookingelementer er: ressursgrupper, utleieobjekter (ressurser), organisasjoner

<strong>Saksbehandlere </strong>kan opprette nye organisasjoner, sende e-post, håndtere søknader og rapportere. For at en saksbehandler skal kunne administrere bygg, sesonger, ukeplaner, faktura og så videre, så må det gis utvidet rettighet (fortrinnsvis som "Superbruker" eller unntaksvis som "Systemadministrator"). 
Gjennom kommandoen
 <strong>BYGG / ANLEGG =&gt; RESSURSER OG SESONGER =&gt; RETTIGHETER </strong>

gis de enkelte brukerne rettigheter til å redigere ulike bygg, ressurser og sesonger.


## Inaktivering av bruker

Brukere skal generelt ikke slettes fra systemet, men settes som <em>inaktiv</em> dersom de ikke lengre skal ha tilgang til systemet. For å gjøre dette velger du:

<strong>ADMINISTRASJON =&gt; ADMIN =&gt; ADMINISTRERE BRUKERE</strong>

Klikk deretter på *Rediger* for den aktuelle brukeren. På det nye skjermbildet  tar du vekk haken for *Bruker er aktiv* og klikker på
![lagre2](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre2.png)

Brukeren er da inaktiv og har ikke lengre tilgang til systemet. Brukeren kan gjøres aktiv igjen om det blir aktuelt, for eksempel etter endt permisjon.

<h2>Brukergrupper</h2>
Første gang administrator logger seg på løsningen, bør det opprettes minst en gruppe for å gi brukere tilgang til Aktivkommune på gruppenivå. Da er det mulig å gi tilgang ved at bruker blir meldt inn i en brukergruppe (saksbehandler, superbruker eller systemadministrator) heller enn å gi enkelttilganger til en ny bruker under *Applikasjoner*.

Du gir en bruker tilgang til grupper via kommandoen:

<strong>ADMINISTRASJON =&gt; ADMIN =&gt; ADMINISTRERE GRUPPER.</strong>

Neste steg vil være [å opprette en kommune eller bydeler/områder.](https://manual.aktiv-kommune.no/?p=291)