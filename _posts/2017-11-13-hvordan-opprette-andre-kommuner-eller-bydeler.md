---
ID: 291
post_title: 'Hvordan opprette kommuner og bydeler/områder? &#8211; IKKE FERDI'
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=291
published: true
post_date: 2017-11-13 13:42:18
---
<blockquote>
Aktivkommune er et system som er har sitt utgangspunkt i FDV-systemet som kalles Portico Estate. FDV står for Forvaltning, Drift og Vedlikehold (av bygg og eiendommer). I Bergen kommune benyttes Portico Estate som FDV-system for de to bygg- og eiendomsforvaltningsetatene. 
Den geografiske inndelingen i FDV-systemet (og dermed også Aktivkommune) er delt inn slik: 
 

<ol>
<li><strong>Instansnavn</strong> (gjerne kommunenavn)</li> 
 
 
<li><strong>Område</strong> (kommunenavn eller områdenavn)</li>
<li><strong>Bydeler</strong> (bydel eller et "mindre" områdenavn; stedsnavn, bygd, dal, øy etc), </li>
<li><strong>Eiendommer</strong> (gårds- og bruksnummer)</li>
<li><strong>Bygg</strong> (navn på bygg/ anlegg)</li>
</ol>
Utleieressursene (ressursgrupper og ressurser) legges på nivå 4 (eiendom) og 5 (bygg). Mer om dette under <strong>rollen "Superbruker", og punktet XXX--kommer senere --XXX</strong>
</blockquote>

(vedlagt figur viser hierarkiet) IKKE FERDIG.....

Hvordan nivå 1 Instansnavn (kommune) ble opprettet ble forklart i avsnittet [hvordan komme i gang med Aktivkommune](http://manual.aktiv-kommune.no/?p=69). I eksempelet under viser vi beste praksis for en kommune som IKKE skal gjennomføre kommunesammenslåing. Vi oppretter først et område (det vil si i praksis en kommune (i systemet kalt lokalisering) og en bydel (for de kommuner som ikke har bydeler kan stedsnavn, bygd, dal, øy brukes). 

Når ett eller flere område(r) og en eller flere bydel(er) er lagt inn, kan eiendom opprettes. Først knytter vi <em>lokalisering</em> til eiendommen for deretter å knytte bygg eller anlegg til <em>eiendommen</em>. I eksempelet under lager vi én eiendom for hele kommunen. 

<h2>Opprette område (lokalisering)</h2>

For å legge inn data om ulike gatenavn, områder og bydeler i kommunen går du til:
<strong>ADMINISTRASJON => EIENDOM => ADMINISTRER LOKALISERING</strong>

Skjermbildet ser da slik ut: 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2018/01/Skjermbildeeiendom.png" alt="skjermbildet eiendom" />
Her ifra velger du <strong>GATE</strong>, <strong>OMRÅDE</strong> (/kommunenavn) eller <strong>BYDEL</strong>(/geografisk område/poststed) avhengig av hva du ønsker å registrere.

I dette eksempelet velger vi <em>bydel</em>:
For å legge til ny bydel klikker du på 

<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png" alt="ny" />
<h2>Fyll inn informasjon om bydel:</h2>

Feltnavn| Forklaring/ Aksjon
--------------------|-----------------------------------
<strong>ID:</strong> |Et fortløpende nummer (som du skriver inn selv).
<strong>Navn:</strong> |Navn på bydel (eller stedsnavn). 
<strong>Leveringsadresse:|</strong> (dette kan være hovedadressen til kommunen) (BRUKES TIL???)
<strong>Område:</strong> |Velg område fra nedtrekksmeny.

Når du er ferdig klikker du på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />

<h2>Opprette eiendom</h2>
Nye eiendommer registreres av en person som har rettigheter som systemadministrator eller superbruker. I eksempelet under lager vi bare én eiendom. For å legge til en eiendom går du til

<strong>EIENDOM => LOKASJON => EIENDOM</strong>

For å registrere ny eiendom klikker du på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png" alt="ny" />
<h2>Fyll inn informasjon om eiendom:</h2>

Feltnavn| Forklaring/ Aksjon
------------------|--------------------------------
<strong>Eiendom:</strong> |Lokasjonskoden til eiendommen (for eksempel: 1246). Lokasjonskoden bør være den samme koden som eiendomsavdelingen i din kommune bruker på eiendommen.
<strong>Navn:</strong> |Navnet på eiendommen (for eksempel: eiendom i Fjell)
<strong>Kategori:</strong> |Velg eiendomskategori fra nedtrekksmenyen eller klikk <a href="https://manual.aktiv-kommune.no/?p=700">her</a> for å legge inn kategorier.
<strong>Bydel</strong> |Velg bydel (eller område/stedsnavn) fra nedtrekksmenyen som eiendommen tilhører. 
<strong>Eier:</strong> |NB! Må være blank.
<strong>Status:</strong> |Velg <em>ok</em> fra nedtrekksmenyen.
<strong>Merknad:</strong> |Hvis det er noe spesielt med eiendommen du ønsker å kommentere, så skriver du det her.
 
De resterende feltene er det ikke behov for å fylle inn.

Når du er ferdig klikker du på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />
<h2>Opprette bygg i Eiendom</h2>


Det mest hensiktsmessige er å opprette <em>alle</em>  kommunens bygg i Eiendoms-modulen. Dette gjøres via kommandoen:

<strong>EIENDOM => LOKASJON => BYGNING</strong>

(NB! om ikke alle bygg er lest inn via et regneark. Kontakt driftsleverandør av Aktivkommune for å få bistand her)

> Det kan i noen sammenhenger se ut som om man gjør litt dobbelarbeid her, for hvorfor skal bygg registreres både i Eiendoms-modulen ("byggregister") og i Bookingmodulen? Forklaringen på det er at det komplette byggregisteret i kommunen (uavhengig av om det skal leies ut eller ikke) er plassert i byggregisteret (Eiendomsmodulen), men at (kun) de ressurser (blant annet bygg) som skal leies ut via Aktivkommune registreres i Bookingmodulen. NB! Det er ingen forutsetning at HELE bygningsregisteret blir registrert inn i Eiendomsmodulen, men det vil forenkle arbeidet senere.

Bygg (og anlegg) legges inn bookingmodulen ved bruk av kommandoen:

<strong>BOOKING => BYGG/ANLEGG</strong> 

(Les mer om hvordan dette gjøres <a href="http://manual.aktiv-kommune.no/?p=321">her</a>.)

Bygget kan da knyttes til bygg eller anlegg i <em>Booking->Bygg/Anlegg</em> med en kombinasjon av <em>Lokaliseringskode</em> og <em>Bygningskode</em> (for eksempel: 1246-1200) i <em>Lokaliseringskode</em>.
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/11/booking_bygg-anlegg-e1511184434853.png" alt="Booking " />

<h2>Knytte bygg til eiendom i Booking</h2>
Når en eiendom er registrert,  så kan det registreres bygg og/eller anlegg som er plassert på eller tilknyttet denne eiendommen. Dette skjer via kommandoen:

<strong>EIENDOM => LOKASJON => BYGNING</strong>

Skjermbildet ser da slik ut: 

<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/eiendombygning.png" alt="skjermbildet bygning" />

Her velger du et bygg for så å klikke på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/rediger.png" alt="rediger" />
I <em>Lokasjonskode</em> skriver du inn koden som ble registrert når du registrerte eiendom (for eksempel 1246 for Fjell).

Når du er ferdig klikker du på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />

Neste steg er <a href="https://manual.aktiv-kommune.no/?p=321">å opprette en bygning.</a>