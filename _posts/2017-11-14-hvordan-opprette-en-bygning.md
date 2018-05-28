---
ID: 321
post_title: Opprette bygg og ressursgrupper
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=321
published: true
post_date: 2017-11-14 11:00:18
---
De to siste elementene som må registreres før selve utleieobjektene (ressursene) kan opprettes (utleieobjekter er beskrevet under rollen saksbehandler), er bygg og ressursgrupper.

Et bygg kan opprettes på to måter i Aktivkommune, og dette ser ved første øyekast både noe tungvint og merkelig ut - for hvorfor blir bygg opprettet to steder?

Dette forklares enklest gjennom et et eksempel:
Et bygg som vi gir navnet "Sandslihallen" har to ressursgrupper som er knyttet til bygget. Vi kalles disse ressursgruppene for "Kanoer Sandslihallen" og "Sandslihallen". Den ene ressursgruppen inneholder utstyr som leies ut (10 kanoer) , og i den andre leies det ut romressurser, for eksempel to basketballhaller, et styrkerom, en klatrevegg og to møterom.

>Begrepet "Bygg" tilhører FDV-dimensjonen av Portico Estate, og registreres i eiendomsmodulen (altså "inngang" via kommandoen EIENDOM). "Bygg" henviser til et fysisk og konkret bygg. I eksempelet over: Selve det fysiske bygget som kalles "Sandslihallen".

>Begrepet "Bygg/anlegg" tilhører bookingmodulen i Portico Estate, og registreres i bookingmodulen (altså "inngang" via kommandoen BOOKING). "Bygg/anlegg" henviser til en <em>ressursgruppe</em> som representerer en gruppe utleieobjekter(ressurser). Denne ressursgruppen har svært ofte en henvisning til det samme fysiske bygget som er omtalt i Eiendomsmodulen, men det kan like gjerne være en gruppe av ressurser som bare har en <em>tilknytning </em> til et fysisk bygg. I eksempelet over: Den ene ressursgruppen som kalles "Kanoer Sandslihallen" er en samling 10 utleiekanoer. Kanoene har base ved bygget "Sandslihallen". Den andre ressursgruppen (som til noens forvirring også kalles "Sandslihallen" og har samme navn som selve bygget) er også tilknyttet til det fysiske bygget "Sandslihallen",  men ressursgruppen "Sandslihallen" refererer altså til <em>innholdet </em> i denne hallen; det vil si alle utleieobjekter(romressurser) som er <em>inne </em> i denne hallen. 

<ul>
 	<li>Oppretting av fysisk bygg i eiendoms-modul skjer gjennom kommandoen:
 <strong>EIENDOM =&gt; LOKASJON =&gt; BYGNING</strong></li>

 	<li>For å opprette en ressursgruppe (det vil i praksis ofte være et bygg eller anlegg) som skal danne en basis for utleieobjekter, må du velge kommandoen:
 <strong>BOOKING =&gt; BYGG/ANLEGG</strong></li>
</ul>

Under "BYGG/ANLEGG" opprettes det følere typer bygg, anlegg og utstyrsgrupper. I bookingsammenheng snakker vi ofte derfor om begrepet "Ressursgruppe", mens i systemet Aktivkommune blir dette kalt "Bygg/anlegg". I starten er disse begrepene gjerne noe forvirrende, men begrepene representerer det samme. 

&gt;Begrepet <strong>"Ressursgruppe"</strong> dekker både:
* <strong>Bygg </strong>(skoler, idrettsbygg, kulturbygg, flerbruksbygg m.m.)
* <strong>Anlegg </strong>(uteanlegg; både idrett og kultur, friluftsområder, parker, torg etc.)
* <strong>Utstyrsgrupper </strong>(flyttbare eller faste installasjoner; f.eks. instrumenter, idrettsutstyr, kanoer, AV-utstyr etc.

.

&gt;Det er bare superbrukere og systemadministratorer som kan legge inn og redigere "Bygg" i Eiendomsmodulen. Og det er bare disse to brukergruppene som kan legge inn og redigere "ressursgrupper" (BYGG/ANLEGG) i Bookingmodulen.

## Opprette bygg i eiendomsmodulen
Før en ressursgruppe skal kunne knyttes til et bygg, må det (fysiske) bygget opprettes (i Eiendomsmodulen). Dette skjer ved bruk av denne kommandoen:

<strong>EIENDOM =&gt; LOKASJON =&gt; BYGNING</strong>

Skjermbildet ser da slik ut:
![skjermbildet bygg](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/eiendombygning.png)

For å registrere et nytt bygg klikker du på
![ny](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png)

## Fyll informasjon om bygget:
Feltnavn| Aksjoner/Forklaringer
---------------|---------------------------------
**Eiendom:** |Et bygg er alltid knyttet til en eiendom, og selve koblingen skjer her: Klikk på ruten og du får opp forslag til lokasjonskoder når du starter å skrive. Velg aktuell kode.
**Bygning:** |Nummer på bygning. Dette kan være et løpenummer, men skal aller helst være samme (unike) kode som eiendomsavdelingen i din kommune har på det aktuelle bygget.
**Navn:** |Navn på bygningen (For eksempel: Sandslihallen)
**Kategori:** |Velg rett kategori (eierforhold) eller klikk [her](https://manual.aktiv-kommune.no/?p=700) for å se hvordan du legger inn ny kategori.
**Adresse:** |Klikk på rute og du får opp forslag til adresser, velg rett gateadresse og nummer.
**Status:** |Velg OK fra nedtrekksmenyen.
**Merknad:** |Hvis det er noe spesielt med bygningen du ønsker å kommentere,  så skriver du det her. Opplysningen er kun til internt bruk.
**Utleieområde:**| ..kan stå uten verdi i bookingsammenheng..
**Bruttoareal:**|.. kan stå uten verdi i bookingsammenheng..
**Nettoareal:**| ..kan stå uten verdi i bookingsammenheng..
**Bruksareal:**| <kan stå uten verdi i bookingsammenheng>

## Opprette ressursgruppe i bookingmodulen


For å opprette en ressursgruppe (det vil si bygg, anlegg eller utstyrsgrupper) i bookingmodulen, må du bruke denne kommandoen:
<strong>BOOKING =&gt; BYGG/ANLEGG </strong>

Mer om hvordan dette gjøres leser du om [her](https://manual.aktiv-kommune.no/?p=166).

Et eksempel: Når du har opprettet et bygg (i Eiendomsmodulen) som heter "Sandslihallen", så må du likevel opprette (minimun) en ressursgruppe (i Bookingmodulen), der den ene ressursgruppen gjerne kan få et navn som også heter "Sandslihallen". Dette skjer gjennom kommandoen "BOOING-> BYGG/ANLEGG". I neste omgang skal det opprettes utleieobjekter(ressurser) som koples på/legges i (ressursgruppen) "Sandslihallen".


<strong>Knytte bygg til en eiendom </strong>

Når du har registrert minimum en eiendom og et bygg i Eiendomsmodulen, er det klart for å koble bygget til aktuell eiendom. Velg kommandoen:

<strong>EIENDOM =&gt; LOKASJON =&gt; BYGNING</strong>

Her velger du et bygg for så å klikke på "Rediger". I <em>Lokasjonskode</em> skriver du inn koden som ble registrert når du registrerte eiendom (vanligvis en tallbasert kode).

Når du er ferdig klikker du på
![lagre](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png)

DENSISTE DELEN HER MÅ FLYTTES ...
<strong>Knytte ressursgrupper i Bookingmodulen til eiendommer eller bygg i Eiendomsmodulen</strong>
Når du har registrert minimum en eiendom eller et bygg i Eiendomsmodulen, er det klart for å registrere ressursgrupper (bygg/anlegg) i bookingmodulen inn mot eiendommen eller bygget. Dette skjer via kommandoen:

&nbsp;