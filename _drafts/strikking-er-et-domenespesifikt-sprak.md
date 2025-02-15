---
layout: post
title: Strikking er et domenespesifikt språk
---
Strikking er inn om dagen. Bestemor strikker, madammen strikker og jeg strikker. For å strikke noe i det hele tatt, for eksempel en genser, så må jeg ha en oppskrift. Jeg finner ikke på ting på egenhånd. I begynnelsen av, for å strikke bolen, oppskriften blir jeg møtt med:

> Legg opp (152) 168-184-200-216 m på rundp 3 1/2 og strikk 10 rekker vrangbord slik: * 2 r, 2 vr *, gjenta fra *—* til slutten av rekken. Skift til rundpinne 4 og strikk 12 rekker perlestrikk slik: Rekke 1: * 1 r, 1 vr *, gjenta til slutten av rekken. Rekke 2: * 1 r, 1 vr *, gjenta *—* til slutten av rekken. Genta rekke 1 og 2 til du har 12 rekker.

Hvis du ikke kan lesestrikkeoppskrifter, så må nok dette fremstå som kaudervelsk. Men det er egentlig ikke så vanskelig. Symbolet ‘m’ står for *maske*, som er et «sting» i det ferdige arbeidet. Det er to masketyper i denne oppskriften, symbolet ‘r’ som står for *rettmaske* og ‘vr’ som står for *vrangmaske*. Listene med tall står for økende størrelser, det miste tallet i parantes står for ekstra liten og det største for ekstra stor. Strikkeren må passe på å velge tallet med samme plassnummer i hele oppskriften. Til slutt så er det symbolet ‘\*—\*’ som betyr gjenta symbolene mellom asteriskene et gitt antall masker.

Men hva minner dette meg om? Jo, dette er jo et programmeringsspråk. Her er det lister som blir indeksert på plassnummer. Det er *while*-løkker med som gjentar en operasjon inntil et vilkår er oppfylt. Strikkeoppskriften er rett og slett en serie imperative, symbolske instruksjoner. Det er egentlig ingen vesentlig forskjell mellom strikkeopskriften og en bit Pyhton-kode.

Vi kan også utrykke oppskriften visuelt som et strikkediagram. Da er en hvit rute en rettmaske og en svart rute en vrangmaske. Resultatet blir da seende slik ut.

Men dette diagrammet ser tilforlatelig likt ut et hullkort. Og det er ikke tilfeldig. De første hullkortene vi kjenner til ble brukt for å styre mønsteret i veve- og strikkemaskiner. Den første maskinen som brukte hullkort ble designet av Jean-Baptiste Falcon 1728 og bruken ble popularisert av Joseph Marie Jacquard og hans Jacquard-vevstol. Vevstolen gjorde det mulig å kunne lage store og kompliserte tekstilmønstere, og tekstilene kunne reproduseres likt gang etter gang. For å lage et gitt mønster trenge man kun de riktige hullkortene.

Ideen med at hullkort kunne brukes til å lagre intruksjoner som så kunne brukes til å «instruere» en generell regnemaskin ble plukket opp av Charles Babbadge
