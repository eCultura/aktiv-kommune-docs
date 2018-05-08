---
ID: 291
post_title: Opprette områder, bydeler og eiendommer
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=291
published: true
post_date: 2017-11-13 13:42:18
---
<blockquote>Aktiv kommune deler inn kommunen i 5 nivå:
<ul>
 	<li><strong>Instansnavn</strong> (kommunenavn)</li>
        <li><strong>Område</strong> (kommunenavn eller områdenavn)</li>
        <li><strong>Bydeler</strong> (bydel eller et "mindre" områdenavn; stedsnavn, bygd, dal, øy etc),</li>
        <li><strong>Eiendommer</strong> (gårds- og bruksnummer)</li>
        <li><strong>Bygg</strong> (navn på bygg/ anlegg)</li>
 	
 	
 	
</ul>
Hver eiendom eller bygg kan ha flere utleieobjekter/ressurser til utleie eller utlån (de deles ressursgrupper og ressurser)</blockquote>
Instansnavn er høyeste nivå (1). I avsnittet [Hvordan komme i gang med Aktiv kommune](http://manual.aktiv-kommune.no/?p=69) forklares opprettelsen av instansnavnet.

I eksempelet under viser vi beste praksis for en kommune som IKKE skal gjennomføre kommunesammenslåing. 

For å legge inn data om ulike gatenavn, områder og bydeler i kommunen, må følgende kommando brukes (flere ganger):
<strong>ADMINISTRASJON =&gt; EIENDOM =&gt; ADMINISTRER LOKALISERING</strong>

Skjermbildet ser da slik ut:
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2018/01/Skjermbildeeiendom.png" alt="skjermbildet eiendom" />
Her ifra velger du <strong>GATE</strong>, <strong>OMRÅDE</strong> (/kommunenavn) eller <strong>BYDEL</strong>(/geografisk område/poststed) avhengig av hva du ønsker å registrere.

Stegene som må gjennomføres før oppstart er disse:

### 1. Opprette gatenavn
Velg: ADMINISTRASJON => EIENDOM => ADMINISTRER LOKALISERING => GATE.
Alle gater/veier som (senere i installasjonen) skal knyttes til utleieobjekter må registreres.


Feltnavn| Forklaring/ Aksjon
----------------------|-----------------------------------
<strong>ID:</strong> |  Et fortløpende nummer (som du skriver inn selv). Dette kan også være ID-en som brukes kommunens gateregister (hentet fra matrikkelen).
<strong>Navn:</strong> |  Skriv inn selve gatenavnet.

Når du er ferdig klikker du på
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />

Minimum en gate/vei må registreres for instansen. 
Gateregisteret til kommunen kan også leses inn maskinelt (via et Excel-ark).

### 2. Opprette område
Velg: ADMINISTRASJON => EIENDOM => ADMINISTRER LOKALISERING => OMRÅDE

Instans er alt opprettet (av driftsoperatør av Aktivkommune; Stavanger kommune).
Under instans er neste nivå <em>områder</em>. 

>På sett og vis er <em>område </em>det høyeste nivået under instansen, og ofte vil navn på område være det samme som navnet på instansen (kommunenavnet). Dette gjelder for kommuner som <strong>ikke</strong> skal utføre kommunesammenslåing. Skal din kommune slås sammen med andre kommuner, ta kontakt med support i Stavanger, så skal du få råd om hvordan område skal fylles ut for å sikre en god kommunesammenslåing senere.

For å legge til et nytt område klikker du på

<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png" alt="ny" />

#### Fyll inn aktuell informasjon om området:

Feltnavn| Forklaring/ Aksjon
-----------------------|-----------------------------------
<strong>ID:</strong> |  Et fortløpende nummer (som du skriver inn selv).
<strong>Navn:</strong> |  Navn på bydel/område (eller stedsnavn).

Når du er ferdig klikker du på
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />

Minimum ett område må opprettes før bydeler kan registreres (se under).

### 3. Opprette bydel.
Velg ADMINISTRASJON => EIENDOM => ADMINISTRER LOKALISERING => BYDEL

For de kommuner som ikke har bydeler, så kan ordet "bydel" tilsvare enten navn på et sted/område, en bygd, en dal, en øy etc.
En bydel er alltid koplet på et (og bare ett) område.
Minimum en bydel må opprettes før eiendommer kan registreres (se under)
 
> NB! Det er de steder/bydeler som opprettes her som vises som valg i Aktivkommune - frontend, men da under begrepet "Område". Det kan være litt forvirrende da vi i backend av Aktivkommune omtaler både område (se over) og bydeler (dette avsnittet). Når ett eller flere område(r) og en eller flere bydel(er) er lagt inn, kan eiendom opprettes. En eiendom er alltid knyttet til en bydel (eller stedsnavn; se over). Først knytter vi <em>lokaliseringskoden</em> til eiendommen til en bydel/stedsnavn.

For å legge til ny bydel klikker du på

<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png" alt="ny" />

#### Fyll inn aktuell informasjon om bydel:

Feltnavn| Forklaring/ Aksjon
----------------------|-----------------------------------
<strong>ID:</strong> |  Et fortløpende nummer (som du skriver inn selv).
<strong>Navn:</strong> |  Navn på bydel (eller stedsnavn).
<strong>Leveringsadresse:|</strong> (dette kan være hovedadressen til kommunen) (BRUKES TIL???)
<strong>Område:</strong> |  Velg område fra nedtrekksmeny.

Når du er ferdig klikker du på
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />

Minimum en bydel må registreres før eiendommer kan opprettes.

<h2>Opprette eiendom</h2>
Nye eiendommer registreres av en person som har rettigheter som systemadministrator eller superbruker. I eksempelet under lager vi bare én eiendom. For å legge til en eiendom går du til

<strong>EIENDOM =&gt; LOKASJON =&gt; EIENDOM</strong>

For å registrere ny eiendom klikker du på
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png" alt="ny" />

#### Fyll inn informasjon om eiendom:

Feltnavn| Forklaring/ Aksjon
------------------|--------------------------------
<strong>Eiendom:</strong> |  Lokasjonskoden til eiendommen (for eksempel: 1246). Lokasjonskoden bør være den samme koden som eiendomsavdelingen i din kommune bruker på eiendommen.
<strong>Navn:</strong> |  Navnet på eiendommen (for eksempel: eiendom i Fjell)
<strong>Kategori:</strong> |  Velg eiendomskategori fra nedtrekksmenyen eller klikk <a href="https://manual.aktiv-kommune.no/?p=700">her</a> for å legge inn kategorier.
<strong>Bydel</strong> |  Velg bydel (eller område/stedsnavn) fra nedtrekksmenyen som eiendommen tilhører.
<strong>Eier:</strong> |  NB! Må være blank.
<strong>Status:</strong> |  Velg <em>ok</em> fra nedtrekksmenyen.
<strong>Merknad:</strong> |  Hvis det er noe spesielt med eiendommen du ønsker å kommentere, så skriver du det her.

De resterende feltene er det ikke behov for å fylle inn.

Når du er ferdig klikker du på
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />

Minimum en eiendom må opprettes før bygg kan opprettes/registreres.

&nbsp;

Neste steg er <a href="https://manual.aktiv-kommune.no/?p=321">å opprette en bygning.</a>