---
ID: 321
post_title: >
  Hvordan opprette et bygg og en
  ressursgruppe?
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=321
published: true
post_date: 2017-11-14 11:00:18
---
Dette punktet kan i utgangspunktet virke noe forvirrende, for hvorfor er det to måter å opprette et bygg (og samme bygg) på i systemet? Forklaringen er denne:
Oppretter du et bygg via Eiendoms-modulen, så registrerer du det fysiske bygget og kun det. Opprettelse av bygget gjøres via kommandoen:
<strong>EIENDOM => LOKASJON => BYGNING</strong>

Dette bygget kan ikke leies ut (fordi det ikke er registrert i Booking-modulen)

Men oppretter du et bygg i Booking-modulen, så oppretter du bygget og klargjør dette samtidig for utleie (NB! Ressurs må også kobles på senere). Opprettelse av bygget (egentlig ressursgruppen) gjøres via kommandoen:
<strong>BOOKING => BYGG/ANLEGG</strong>

Men kommandoen "BOOKING=>BYGG/ANLEGG" kan gjøre mer enn å bare å opprette bygg. Den brukes også til å opprette anlegg og utstyrsgrupper - som også kan utgjøre en basis for utleie av (enkelt)ressurser. Begrepet "BYGG/ANLEGG" er derfor noe misvisende, og det kan hende at vi på sikt bytter dette begrepet ut med et annet begrep. I bookingsammenheng snakker vi ofte om begrepet "Ressursgruppe". 

>Begrepet <strong>"Ressursgruppe"</strong> dekker både:
* <strong>Bygg </strong>(skoler, idrettsbygg, kulturbygg, flerbruksbygg m.m.)
* <strong>Anlegg </strong>(uteanlegg; både idrett og kultur, friluftsområder, parker, torg etc.) 
* <strong>Utstyrsgrupper </strong>(flyttbare eller faste installasjoner; f.eks. instrumenter, idrettsutstyr, kanoer, AV-utstyr etc. 

I sammenheng med Aktivkommune  blir kommandoen "BYGG/ANLEGG" ofte omtalt som en "Ressursgruppe"; der en ressursgruppe kan inneholde en samling med (utleie)ressurser.

>Det er bare superbrukere og administratorer som kan legge inn og redigere "Bygg" i Eiendomsmodulen. Og det er bare disse brukergruppene som kan legge inn og redigere "ressursgrupper" (BYGG/ANLEGG) i Bookingmodulen.

### Opprette bygg(, anlegg og utstyrsgrupper) i bookingmodulen

For å opprette bygg, anlegg og utstyrsgrupper i bookingmodulen bruks følgende kommando:
<strong>BOOKING => BYGG/ANLEGG </strong>

Mer om hvordan dette gjøres leser du om [her](https://manual.aktiv-kommune.no/?p=166).

### Opprette bygg i eiendomsmodulen
For å opprette et bygg brukes følgende kommando

<strong>EIENDOM => LOKASJON => BYGNING</strong>

Skjermbildet ser da slik ut:
![skjermbildet bygg](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/eiendombygning.png)

For å registrere et nytt bygg klikker du på
![ny](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png)

## Fyll informasjon om bygget: 
Feltnavn| .      .
---------------|---------------------------------
**Eiendom:** |Klikk på ruten og du får opp forslag til lokasjonskoder, velg rett kode.
**Bygning:** |Nummer på bygning. Dette er et løpende nummer.
**Navn:** |Navn på bygningen (For eksempel: Sandslihallen)
**Kategori:** |Velg rett kategori eller klikk [her](https://manual.aktiv-kommune.no/?p=700) for å se hvordan du legger inn ny kategori.
**Adresse:** |Klikk på rute og du får opp forslag til adresser, velg rett adresse.
**Status:** |Velg OK fra nedtrekksmenyen.
**Merknad:** |Hvis det er noe spesielt med bygningen du ønsker å kommentere så skriver du det her. 
**Utleieområde:**|<brukes foreløpig ikke i bookingsammenheng>
**Bruttoareal:**|<brukes foreløpig ikke i bookingsammenheng>
**Nettoareal:**|<brukes foreløpig ikke i bookingsammenheng>
**Bruksareal:**|<brukes foreløpig ikke i bookingsammenheng>

Når du er ferdig klikker du på 
![lagre](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png)