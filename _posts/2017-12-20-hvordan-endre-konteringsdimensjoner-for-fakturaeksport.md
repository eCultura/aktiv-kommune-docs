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

Skjermbildet ser da slik ut: 
![skjermbilde konteringsdimensjoner]()
LEGG INN SKJERMBILDE NÅR SKRIFTEN ER RETTET!!!!!!

Under "Ekstern kontering"(på engelsk '!external account'" er det for output-formatet lagt inn "Agresso" som 'default'-verdi. Bruker din kommune Visma som økonomisystem, så klikker du på nedtrekksmenyen og velger Visma 

>Du kan også endre til andre systemer om dette er ønskelig. Disse systemene må i så fall få tilpasset en egen integrasjon. Meld fra til driftleverandør (Stavanger) om dette trengs. 



Når du har lagt inn aktuelle opplysninger, klikker du på 
![lagre](http://manual.aktiv-kommune.no/wp-content/uploads/2017/12/lagre.png)