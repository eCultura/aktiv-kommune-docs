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

Alle gater/veier som (senere i installasjonen) skal knyttes til utleieobjekter må registreres.

For å registrere et gatenavn velger du

<strong>ADMINISTRASJON => EIENDOM => ADMINISTRER LOKALISERING => GATE.</strong>

og klikk deretter på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png" alt="ny" />

#### Skriv inn aktuell informasjon i det nye skjermbildet:


Feltnavn| Forklaring/ Aksjon
----------------------|-----------------------------------
<strong>ID:</strong> |  Et fortløpende nummer (som du skriver inn selv). Dette kan med fordel være gate-ID-en som brukes kommunens gateregister (hentet fra matrikkelen).
<strong>Navn:</strong> |  Skriv inn selve gatenavnet.

Når du er ferdig klikker du på
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />

Minimum en gate/vei må registreres for instansen. 
Gateregisteret til kommunen kan også leses inn maskinelt (via et Excel-ark).



### 2. Opprette område

Instans er alt opprettet (av driftsoperatør av Aktivkommune; Stavanger kommune).
Under instans er neste nivå <em>områder</em>. 

>På sett og vis er <em>område </em>det høyeste nivået under instansen, og ofte vil navn på område være det samme som navnet på instansen (kommunenavnet). Dette gjelder for kommuner som <strong>ikke</strong> skal utføre kommunesammenslåing. Skal din kommune slås sammen med andre kommuner, ta kontakt med support i Stavanger, så skal du få råd om hvordan område skal fylles ut for å sikre en god kommunesammenslåing senere.

For å legge til et nytt område velger du:
<strong>ADMINISTRASJON => EIENDOM => ADMINISTRER LOKALISERING => OMRÅDE</strong>

og deretter klikker du på:

<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png" alt="ny" />

#### Fyll inn aktuell informasjon om området:

  Feltnavn   | Forklaring/ Aksjon
-----------------------|-----------------------------------
<strong>ID:</strong> |  Et fortløpende nummer (som du skriver inn selv).
<strong>Navn:</strong> |  Navn på bydel/område (eller stedsnavn).

Når du er ferdig klikker du på
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />

Minimum ett område må opprettes før bydeler kan registreres (se under).


### 3. Opprette bydel.
En bydel er alltid er alltid knyttet til et (og bare ett) område (i systemet)

> For de kommuner som ikke har bydeler, så kan ordet "bydel" tilsvare enten navn på et sted/område, en bygd, en dal, en øy etc.


 
> NB! Det er de steder/bydeler som opprettes her som vises som valg i Aktivkommune - frontend, men da under begrepet "Område". Det kan være litt forvirrende da vi i backend av Aktivkommune omtaler både område (se over) og bydeler (dette avsnittet). Når ett eller flere område(r) og en eller flere bydel(er) er lagt inn, kan eiendom opprettes. En eiendom er alltid knyttet til en bydel (eller stedsnavn; se over). Først knytter vi <em>lokaliseringskoden</em> til eiendommen til en bydel/stedsnavn.

For å legge til ny bydel velger du:

<strong>ADMINISTRASJON => EIENDOM => ADMINISTRER LOKALISERING => BYDEL</strong>

og deretter klikker du på 
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png" alt="ny" />

#### Fyll inn aktuell informasjon om bydel:

Feltnavn| Forklaring/ Aksjon
----------------------|-----------------------------------
<strong>ID:</strong> |  Et fortløpende nummer (som du skriver inn selv).
<strong>Navn:</strong> |  Navn på bydel (eller stedsnavn).
<strong>Leveringsadresse:|</strong> (dette kan være hovedadressen til kommunen) (BRUKES TIL???)
<strong>Område:</strong> |  Velg område som "bydelen/stedsnavnet tilhører fra nedtrekksmeny (dette er opprettet under "Område").

Når du er ferdig klikker du på
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png" alt="lagre" />

Minimum en bydel må opprettes før eiendommer kan opprettes.


<h2>4. Opprette eiendom</h2>
> Eiendommer er som regel avgrenset av gårds- og bruksnummer, men det er mulig å splitte dette ytterligere opp om det er aktuelt.

En eiendom skal alltid knyttes til en (og bare en) "bydel"/"stedsnavn", og som er registrert i punkt 3 over. 

For å opprette en ny eiendom velger du:
<strong>EIENDOM =&gt; LOKASJON =&gt; EIENDOM</strong>

og deretter klikker du på:
<img src="http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/NY.png" alt="ny" />


#### Fyll inn aktuell informasjon om eiendom:

Feltnavn       | Forklaring/ Aksjon
------------------|--------------------------------
 <strong>Eiendom:</strong> |  Lokasjonskoden til eiendommen (for eksempel: 1246). Lokasjonskoden bør (helst) være den samme koden som eiendomsavdelingen i din kommune bruker på eiendommen.
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