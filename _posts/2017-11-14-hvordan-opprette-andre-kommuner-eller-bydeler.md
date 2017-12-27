---
ID: 291
post_title: >
  Hvordan opprette andre kommuner eller
  bydeler?
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=291
published: true
post_date: 2017-11-14 13:42:18
---
Dette beskriver en minimumsløsning for hvordan opprette flere kommuner eller bydeler i AktivKommune. I eksempelet under oppretter vi en kommune (lokalisering) og en eiendom. Først knytter vi *lokalisering* til eiendommen for deretter å knytte bygg eller anlegg til *eiendommen*. I eksempelet under lager vi én eiendom for hele kommunen.

## Opprette lokalisering

For å legge inn data om ulike gatenavn, områder og bydeler i kommunen går du til:

ADMINISTRASJON => EIENDOM => ADMINISTRER LOKALOSERING

Skjembildet ser da slik ut: 
![skjermbildet eiendom](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/eiendom.png)

Velg *Administrasjon->Eiendom->Registrer lokalisering->Bydel*.
- Klikk *Ny*
- Skriv inn *ID* (Et fortløpende nummer)
- Skriv inn *Navn* (Navn på kommune eller bydel)
- Lagre

![Bydel](http://manual.aktiv-kommune.no/wp-content/uploads/2017/11/lokalisering_bydel-e1511167484971.png)

## Opprette eiendom
I eksempelet under lager vi bare én eiendom for hver kommune.

Gå til *Eiendom->Lokalisering->Eiendom*.

- Klikk *Ny*
- Skriv inn *Eiendom* (eks.: 1246)
- Skriv inn *Navn* (eks.: Eigedom i Fjell)
- Velg *SOMETHING* i *Kategori* eller les [her](#) for å legge inn Kategorier
- Velg *Bydel* som tidligere er lagt inn i avsnittet over 
- Eier må være *blank*
- Lagre

![Eiendom](http://manual.aktiv-kommune.no/wp-content/uploads/2017/11/eiendom_lokalisering-e1511170040257.png)

## Knytte bygg til eiendom i Booking
I *Booking->Bygg/Anlegg*
- Klikk på et bygg
- Velg *Rediger*
- I *Lokasjonskode* skriver du inn kode som ble registrert i Eiendom->Lokalisering->Eiendom (eks. 1246 for Fjell)
- Husk å lagre endringene

![Lokasjonskode](http://manual.aktiv-kommune.no/wp-content/uploads/2017/11/lokasjonskode-e1511173813483.png)

## Opprette bygg i Eiendom
Det mest hensiktsmessige er å opprette alle kommunens bygg i *Eiendom->Lokalisering->Bygning*, ikke bare i *Booking->Bygg/Anlegg*. Les mer om hvordan dette gjøres [her](http://manual.aktiv-kommune.no/?p=321).

Bygget kan da knyttes til bygg eller anlegg i *Booking->Bygg/Anlegg* med en kombinasjon av *Lokaliseringskode* og *Bygningskode* (eks.: 1246-1200) i *Lokaliseringskode*.

![Booking ](http://manual.aktiv-kommune.no/wp-content/uploads/2017/11/booking_bygg-anlegg-e1511184434853.png)