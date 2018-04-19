---
ID: 291
post_title: 'Hvordan opprette kommuner og bydeler/områder &#8211; IKKE FERDI?'
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=291
published: true
post_date: 2017-11-13 13:42:18
---
Aktivkommune er et system som er tett knyttet opp mot fagområdet bygg- og eiendomsforvaltning. I Bergen kommune benyttes systemet også som FDV-system for de to byggforvaltningsetatene. 

Den geografiske plasseringen er delt inn slik:
1. Kommunenavn (instans)
2. Område
3. Bydeler 
4. Eiendommer
5. Bygg

(vedlagt figur viser hierarkiet) IKKE FERDIG.....

Dette beskriver en minimumsløsning for hvordan opprette flere kommuner eller bydeler i Aktivkommune. I eksempelet under oppretter vi en kommune (lokalisering) og en eiendom. Først knytter vi *lokalisering* til eiendommen for deretter å knytte bygg eller anlegg til *eiendommen*. I eksempelet under lager vi én eiendom for hele kommunen.

## Opprette lokalisering 

For å legge inn data om ulike gatenavn, områder og bydeler i kommunen går du til:

<strong>ADMINISTRASJON => EIENDOM => ADMINISTRER LOKALISERING</strong>

Skjermbildet ser da slik ut: 
![skjermbildet eiendom](http://manual.aktiv-kommune.no/wp-content/uploads/2018/01/Skjermbildeeiendom.png)

Her ifra velger du GATE, OMRÅDE (/kommunenavn) eller BYDEL(/geografisk område/poststed) avhengig av hva du ønsker å registrere. 

I dette eksempelet valgte vi bydel:

For å legge til ny bydel klikker du på 
![ny](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png)

## Fyll inn informasjon om bydel:
**ID:** Et fortløpende nummer.
**Navn:** Navn på bydel. 
**Leveringsadresse:**
**Område:** Velg område fra nedtrekksmeny.

Når du er ferdig klikker du på 
![lagre](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png)


## Opprette eiendom
Nye eiendommer registreres av systemansvarlige. I eksempelet under lager vi bare én eiendom for hver kommune. For å legge til en eiendom går du til

EIENDOM => LOKASJON => EIENDOM 

For å registrere ny eiendom klikker du på 
![ny](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png)

## Fyll inn informasjon om eiendom:
**Eiendom:** Lokasjonskoden til eiendommen (for eksempel: 1246)
**Navn:** Navnet på eiendommen (for eksempel: eiendom i Fjell)
**Kategori:** Velg eiendomskategori fra nedtrekksmenyen eller klikk [her](https://manual.aktiv-kommune.no/?p=700) for å legge inn kategorier.
**Bydel** Velg bydel fra nedtrekksmenyen som eiendommen går under. 
**Eier:** Må være blank.
**Status:** Velg *ok* fra nedtrekksmenyen.
**Merknad:** Hvis det er noe spesielt med eiendommen du ønsker å kommentere så skriver du det her. 
De resterende feltene er det ikke behov for å fylle inn.

Når du er ferdig klikker du på 
![lagre](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png)


## Opprette bygg i Eiendom
Det mest hensiktsmessige er å opprette alle kommunens bygg i 

EIENDOM => LOKASJON => BYGNING

og ikke bare i 

BOOKING => BYGG/ANLEGG (Les mer om hvordan dette gjøres [her](http://manual.aktiv-kommune.no/?p=321).)

Bygget kan da knyttes til bygg eller anlegg i *Booking->Bygg/Anlegg* med en kombinasjon av *Lokaliseringskode* og *Bygningskode* (for eksempel: 1246-1200) i *Lokaliseringskode*.

![Booking ](http://manual.aktiv-kommune.no/wp-content/uploads/2017/11/booking_bygg-anlegg-e1511184434853.png)

## Knytte bygg til eiendom i Booking
Når en eiendom er registrert så må det registreres minst ett bygg/anlegg som tilhører eiendommen.  

EIENDOM => LOKASJON => BYGNING

Skjermbildet ser da slik ut: 
![skjermbildet bygning](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/eiendombygning.png)

Her velger du et bygg for så å klikke på 
![rediger](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/rediger.png)
I *Lokasjonskode* skriver du inn koden som ble registrert når du registrerte eiendom (for eksempel 1246 for Fjell).

Når du er ferdig klikker du på 
![lagre](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png)

Neste steg er [å opprette en bygning.](https://manual.aktiv-kommune.no/?p=321)