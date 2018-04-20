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
<blockquote>
  Aktivkommune er et system som er tett knyttet opp mot fagområdet bygg- og eiendomsforvaltning. I Bergen kommune benyttes systemet også som FDV-system for de to byggforvaltningsetatene. Den geografiske inndeling er delt inn slik:
</blockquote>

<ol>
<li>Kommunenavn (instans)</li>
<li>Område</li>
<li>Bydeler </li>
<li>Eiendommer</li>
<li>Bygg</li>
</ol>

Utleieressursene (ressursgrupper og ressurser) legges på nivå 4 (eiendom) og 5 (bygg). Mer om dette under <strong>rollen "Superbruker", og punktet XXX--kommer senere --XXX</strong>

(vedlagt figur viser hierarkiet) IKKE FERDIG.....

Hvordan nivå 1 (instans) ble opprettet ble forklart i avsnittet [hvordan komme i gang med Aktivkommune.]( <a href="http://manual.aktiv-kommune.no/?p=69"></a> eller bydeler i Aktivkommune. I eksempelet under oppretter vi en kommune (lokalisering) og en eiendom. Først knytter vi <em>lokalisering</em> til eiendommen for deretter å knytte bygg eller anlegg til <em>eiendommen</em>. I eksempelet under lager vi én eiendom for hele kommunen.

<h2>Opprette lokalisering</h2>

For å legge inn data om ulike gatenavn, områder og bydeler i kommunen går du til:

<strong>ADMINISTRASJON => EIENDOM => ADMINISTRER LOKALISERING</strong>

Skjermbildet ser da slik ut: 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2018/01/Skjermbildeeiendom.png" alt="skjermbildet eiendom" />

Her ifra velger du GATE, OMRÅDE (/kommunenavn) eller BYDEL(/geografisk område/poststed) avhengig av hva du ønsker å registrere.

I dette eksempelet valgte vi bydel:

For å legge til ny bydel klikker du på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png" alt="ny" />

<h2>Fyll inn informasjon om bydel:</h2>

<strong>ID:</strong> Et fortløpende nummer.
<strong>Navn:</strong> Navn på bydel. 
<strong>Leveringsadresse:</strong>
<strong>Område:</strong> Velg område fra nedtrekksmeny.

Når du er ferdig klikker du på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />

<h2>Opprette eiendom</h2>

Nye eiendommer registreres av systemansvarlige. I eksempelet under lager vi bare én eiendom for hver kommune. For å legge til en eiendom går du til

EIENDOM => LOKASJON => EIENDOM

For å registrere ny eiendom klikker du på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png" alt="ny" />

<h2>Fyll inn informasjon om eiendom:</h2>

<strong>Eiendom:</strong> Lokasjonskoden til eiendommen (for eksempel: 1246)
<strong>Navn:</strong> Navnet på eiendommen (for eksempel: eiendom i Fjell)
<strong>Kategori:</strong> Velg eiendomskategori fra nedtrekksmenyen eller klikk <a href="https://manual.aktiv-kommune.no/?p=700">her</a> for å legge inn kategorier.
<strong>Bydel</strong> Velg bydel fra nedtrekksmenyen som eiendommen går under. 
<strong>Eier:</strong> Må være blank.
<strong>Status:</strong> Velg <em>ok</em> fra nedtrekksmenyen.
<strong>Merknad:</strong> Hvis det er noe spesielt med eiendommen du ønsker å kommentere så skriver du det her. 
De resterende feltene er det ikke behov for å fylle inn.

Når du er ferdig klikker du på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />

<h2>Opprette bygg i Eiendom</h2>

Det mest hensiktsmessige er å opprette alle kommunens bygg i

EIENDOM => LOKASJON => BYGNING

og ikke bare i

BOOKING => BYGG/ANLEGG (Les mer om hvordan dette gjøres <a href="http://manual.aktiv-kommune.no/?p=321">her</a>.)

Bygget kan da knyttes til bygg eller anlegg i <em>Booking->Bygg/Anlegg</em> med en kombinasjon av <em>Lokaliseringskode</em> og <em>Bygningskode</em> (for eksempel: 1246-1200) i <em>Lokaliseringskode</em>.

<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/11/booking_bygg-anlegg-e1511184434853.png" alt="Booking " />

<h2>Knytte bygg til eiendom i Booking</h2>

Når en eiendom er registrert så må det registreres minst ett bygg/anlegg som tilhører eiendommen.

EIENDOM => LOKASJON => BYGNING

Skjermbildet ser da slik ut: 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/eiendombygning.png" alt="skjermbildet bygning" />

Her velger du et bygg for så å klikke på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/rediger.png" alt="rediger" />
I <em>Lokasjonskode</em> skriver du inn koden som ble registrert når du registrerte eiendom (for eksempel 1246 for Fjell).

Når du er ferdig klikker du på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />

Neste steg er <a href="https://manual.aktiv-kommune.no/?p=321">å opprette en bygning.</a>