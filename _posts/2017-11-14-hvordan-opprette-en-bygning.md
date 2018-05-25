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

Et bygg kan opprettes på to måter i Aktivkommune, og dette ser ved første øyekast både noe tungvint og merkelig ut - for hvorfor blir bygg opprettet to steder?:
Forklaringen er denne:

Begrepet "Bygg" tilhører FDV-dimensjonen av Portico Estate, og registreres i eiendomsmodulen (altså "inngang" via kommandoen EIENDOM).
Begrepet "Bygg/anlegg" tilhører bookingmodulen i Portico Estate, og registreres i bookingmodulen (altså "inngang" via kommandoen BOOKING)


<ul>
 	<li>Oppretting av fysisk bygg i eiendoms-modul skjer gjennom kommandoen:
 <strong>EIENDOM =&gt; LOKASJON =&gt; BYGNING</strong></li>

 	<li>For å klargjøre et bygg (eller anlegg) for utleie, må du velge kommandoen:
 <strong>BOOKING =&gt; BYGG/ANLEGG</strong> (NB! Utleieobjekt (ressurs) må også kobles på senere)</li>
</ul>

Under "BYGG/ANLEGG" opprettes bygg, anlegg og utstyrsgrupper som utgjør en basis for utleie av ressurser. I bookingsammenheng snakker vi ofte derfor om begrepet "Ressursgruppe", mens i systemet Aktivkommune blir dette kalt "Bygg/anlegg".

&gt;Begrepet <strong>"Ressursgruppe"</strong> dekker både:
* <strong>Bygg </strong>(skoler, idrettsbygg, kulturbygg, flerbruksbygg m.m.)
* <strong>Anlegg </strong>(uteanlegg; både idrett og kultur, friluftsområder, parker, torg etc.)
* <strong>Utstyrsgrupper </strong>(flyttbare eller faste installasjoner; f.eks. instrumenter, idrettsutstyr, kanoer, AV-utstyr etc.

I sammenheng med Aktivkommune blir kommandoen "BYGG/ANLEGG" like ofte omtalt som en "Ressursgruppe"; 
En ressursgruppe er en samling med (utleie)ressurser.

&gt;Det er bare superbrukere og systemadministratorer som kan legge inn og redigere "Bygg" i Eiendomsmodulen. Og det er bare disse to brukergruppene som kan legge inn og redigere "ressursgrupper" (BYGG/ANLEGG) i Bookingmodulen.

## Opprette bygg i eiendomsmodulen
For å opprette et (fysisk) bygg brukes følgende kommando:

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
**Utleieområde:**| <kan stå uten verdi i bookingsammenheng>
**Bruttoareal:**|<kan stå uten verdi i bookingsammenheng>
**Nettoareal:**| <kan stå uten verdi i bookingsammenheng>
**Bruksareal:**| <kan stå uten verdi i bookingsammenheng>

## Opprette bygg, anlegg og utstyrsgrupper i bookingmodulen

For å opprette bygg, anlegg og utstyrsgrupper i bookingmodulen bruks følgende kommando:
<strong>BOOKING =&gt; BYGG/ANLEGG </strong>

Mer om hvordan dette gjøres leser du om [her](https://manual.aktiv-kommune.no/?p=166).

<strong>Knytte bygg til eiendom i Booking</strong>

Når en eiendom er registrert, så kan det registreres bygg og/eller anlegg som er plassert på eller tilknyttet denne eiendommen. Dette skjer via kommandoen:

<strong>EIENDOM =&gt; LOKASJON =&gt; BYGNING</strong>

Her velger du et bygg for så å klikke på "Rediger". I <em>Lokasjonskode</em> skriver du inn koden som ble registrert når du registrerte eiendom (sifferkode).

Når du er ferdig klikker du på
![lagre](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png)

&nbsp;