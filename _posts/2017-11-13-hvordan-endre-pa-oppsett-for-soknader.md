---
ID: 281
post_title: >
  Konfigurere innstillinger for nettside,
  standard e-poster, språk og
  søknadsoppsett
author: Arild M. Halvorsen
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=281
published: true
post_date: 2017-11-13 10:31:59
---
Før oppstart er det også behov for å legge inn litt basisinformasjon i systemet, og samtidig foreta noen valg, for eksempel om [språk](https://manual.aktiv-kommune.no/?p=340). Denne seksjonen beskriver minimum av hva som må registreres for å komme i gang.

# Kort om noen innstillinger for Aktivkommune

Under installasjonen av Aktivkommune må det legges inn informasjon om følgende fire forhold
* URL til nettside, 
* e-post innstillinger og 
* link til logo med kommunevåpen 
* størrelse på foto/ bilder som skal brukes

Velg kommandoen: 
<strong>ADMINISTRASJON =&gt; BOOKING =&gt; KONFIGURASJON</strong>

og følgende skjermbilde dukker opp:

![Skjermbilde-ADM-BOOKING-KONFIGU-600x400](http://manual.aktiv-kommune.no/wp-content/uploads/2018/05/Skjermbilde-ADM-BOOKING-KONFIGU.png)

I løsningen er det mulig (ikke et krav) å legge inn bilder/foto av de ulike utleieobjekter (ressurser). Dersom det legges inn høytoppløselige bilder, kan dette gå utover hastigheten på visningen i frontend. 

For å unngå problemer med omskalering av bilder i nettleser brukes et verktøy kalt Magic. Dette verktøyet skalerer bilder ved opplasting i løsningen ut fra verdier som er lagt inn under «Image maxhight/width» under konfigurasjon. Default verdi er 300x300.

Når du er ferdig med å fylle ut informasjonen, klikker du på
![Lagre] (http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png)

>Det er også mulig å endre på andre forhold i systemet, men vi anbefaler at dette ikke gjøres uten forespørsel til driftsleverandør.


## Endre språk(fil)

Aktivkommune er tilrettelagt for både bokmål og nynorsk, og skal også bli tilrettelagt for samisk. Språket kan endres ved å gjøre følgende:
<div class="entry-content">
<div class="pf-content">
<ul>
 	<li>Gå til SETUP for din kommune (instans) ved å skrive inn følgende URL: 

https://site1.aktiv-kommune.no/<em>[kommunenavn eller instansnavn]</em>/setup/</li>
 	<li>Logg inn med brukernavn og passord </li>
 	<li>Velg <em>Manage Languages</em></li>
 	<li>Velg <em>Install</em></li>


</ul>

>NB! Du må være superbruker eller systemadministrator for å kunne endre i SETUP (passord er sendt til systemadministrator i kommunen i egen e-post) </li>

</div>
</div>

## Endre oppsett for søknadsskjema

Det er også mulig å endre noe på oppsettet for hvordan søknadsskjemaet skal se ut. For å gjøre dette velger du kommandoen:

<strong>BOOKING =&gt; INNSTILLINGER =&gt; SØKNADS OPPSETT</strong>

Skjermbildet ser da slik ut:
![skjermbildet søknadsoppsett](http://manual.aktiv-kommune.no/wp-content/uploads/2018/02/soknadsoppsett.png)

Endringene som gjøres her påvirker hjelpeteksten på søknaden i frontend.

Det er lagt inn standardiserte tekster, men du kan foreta endringer på disse tekstene. Husk at det må være korte og presise formuleringer. For mye tekst vil kunne "trøtte" ut publikum, informasjonen vil trolig ikke bli lest om det blir (for) mye informasjon på skjermbildet.

## Fyll ut feltene for oppsettet for søknader:

Hvordan søknadsskjemaet (for publikum og lag/organisasjoner) ser ut, blir bestemt og endret i dette skjermbildet. For råd og tips her, ta gjerne kontakt med driftsoperatør i Stavanger for å få råd om "beste praksis".

Feltnavn | Aksjon / Forklaring
---------------------|-------------------------------------
**Ny søknad:** |Denne teksten kommer i toppen av starten på søknaden i frontend.
**Aktiviteter:** |Denne teksten kommer under "Hvorfor" og over nedtrekksmenyen hvor man velger aktiviterer man skal utføre.
**Informasjon om aktiviteten/arrangementet:** |Denne teksten hører til feltet hvor man gir mer informasjon om aktiviteten man skal utføre.
**Ekstra informasjon på arrangement:** |Teksten hører til feltet hvor man kan opplyse om spesielle behov i forbindelse med arrangementet.
**Hvor mange?** |Teksten hører til den delen av søknaden hvor man må oppgi hvor mange som kommer på arrangementet.
**Hvor?** |Teksten kommer i forbindelse med at man må velge bygg og ressurser som tilhører bygget som man ønsker å leie.
**Når?** |Teksten kommer i forbindelse med at man velger dato og klokkeslett for leieperioden.
**Hvem?** |Teksten kommer i forbindelse med at man skal krysse av for målgruppen for arrangementet. (Dette feltet vil trolig utgå i versjon 2 av systemet)
**Kontaktinformasjon:** |Teksten kommer i forbindelse ved at søker skal oppgi kontaktinformasjonen sin.
**Ansvarlig søker/Fakturainformasjon 1:** Teksten kommer i forbindelse med at søker må oppgi fødselsnummer/organisasjonsnummer for fakturainformasjon.
**Ansvarlig søker/Fakturainformasjon 2:** Teksten kommer i forbindelse med at søker må oppgi fødselsnummer/organisasjonsnummer for fakturainformasjon. Denne teksten kommer etter nedtrekksmenyen.
**Juridiske vilkår 1:** |Teksten kommer i forbindelse med de juridiske vilkårene, over hvor du haker av for at du har akseptert vilkårene.
**Juridiske vilkår 2:** |Teksten kommer i forbindelse med de juridiske vilkårene, under hvor du haker av for at du har akseptert vilkårene.

Når du er ferdig med å fylle ut informasjonen, klikker du på
![Lagre] (http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png)

Neste steg er å registrere områder, bydeler og eiendommer.