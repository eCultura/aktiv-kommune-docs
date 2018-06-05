---
ID: 622
post_title: >
  Hvordan sette opp og endre
  konteringsdimensjoner for
  fakturaeksport?
author: Marie Aune
post_excerpt: ""
layout: post
permalink: http://manual.aktiv-kommune.no/?p=622
published: true
post_date: 2017-12-20 09:59:52
---
Når vi skal generere fakturafil i Aktivkommune, og som skal sendes til et økonomisystem, så må følgende steg gjennomføres. 

>I forkant må det i kommunens økonomisystem opprettes en egen systemkode for AktivKommune. Både VISMA og AGRESSO trenger å vite hvilket fagsystem som leverer data, og importfilen (fakturafilen) fra Aktivkommune må inneholde en egen systemkode som forteller at det er data fra Aktivkommune som skal leses inn. <em>Legge inn eksempel fra LINDÅS??</em>

Velg først kommandoen:

<strong>BOOKING => INNSTILLINGER => KONTERINGSDIMENSJONER</strong>
Et nytt skjermbilde dukker opp, og du må registrere følgende felter:

Feltnavn   |   Aksjon/ Forklaring
-------------------------------|----------------------------------------------
Article (pos 283 - 297)| Vareartikkel. (Selve varekoden og varenavnet registeres under 'konteringsstrenger' - i et annet skjermbilde)
Dim1 (pos 862 - 869)|Skriv inn ordet "Art". /Konteringsdimensjon (VISMA)
Dim2 (pos 870 - 877)|Skriv inn ordet "Ansvar". /Konteringsdimensjon (VISMA)
Dim3 (pos 878 - 885)|Skriv inn ordet "Tjeneste". /Konteringsdimensjon (VISMA)
Dim4 (pos 886 - 893)|..ubrukt..
Dim5 (pos 894 - 905)|Skriv inn ordet "Prosjekt" (default verdi er 9)./ Dette feltet må ha et siffer, ellers feiler fakturafilen
Dim_value_1 (pos 914 - 925)|Skriv inn ordet "Oppdragsgiver"
Dim_value_4 (pos 950 - 961)|
Dim_value_5 (pos 962 - 973)|Skriv inn "Kontakt avd." / Kontaktavdelingkode/navn kommer på faktura.


Skjermbildet for en VISMA-bruker (Lindås kommune) ser eksempelvis slik ut: 
![Oppsett-av-konteringsdimensjoner](http://manual.aktiv-kommune.no/wp-content/uploads/2018/06/Oppsett-av-konteringsdimensjoner.png)
LEGG INN SKJERMBILDE NÅR SKRIFTEN ER RETTET!!!!!!

Under "Ekstern kontering"(på engelsk '!external account'" er det for output-formatet lagt inn "Agresso" som 'default'-verdi. Bruker din kommune Visma som økonomisystem, så klikker du på nedtrekksmenyen og velger Visma 

>Du kan også endre til andre systemer om dette er ønskelig. Disse systemene må i så fall få tilpasset en egen integrasjon. Meld fra til driftleverandør (Stavanger) om dette trengs. 



Når du har lagt inn aktuelle opplysninger, klikker du på 
![lagre](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png)