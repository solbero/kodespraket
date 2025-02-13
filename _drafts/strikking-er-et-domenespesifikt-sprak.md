---
layout: post
title: Strikking er et domenespesifikt språk
---
Strikking er inn om dagen. Bestemor strikker, madammen strikker og jeg strikker. For å strikke noe i det hele tatt, for eksempel en genser, så må jeg ha en oppskrift. Jeg finner ikke på ting på egenhånd. I begynnelsen av, for å strikke bolen, oppskriften blir jeg møtt med:

> Legg opp (152) 168-184-200-216 m på rundp 3 1/2 og strikk 10 rekker vrangbord slik: * 2 r, 2 vr *, gjenta fra *—* til slutten av rekken. Skift til rundpinne 4 og strikk 12 rekker perlestrikk slik: Rekke 1: * 1 r, 1 vr *, gjenta til slutten av rekken. Rekke 2: * 1 r, 1 vr *, gjenta *—* til slutten av rekken. Genta 6 ganger rekke 1 og 2.

Hvis du ikke kan lesestrikkeoppskrifter, så må nok dette fremstå som kaudervelsk. Men det er egentlig ikke så vanskelig. Symbolet ‘m’ står for *maske*, som er et «sting» i det ferdige arbeidet. Det er to masketyper i denne oppskriften, symbolet ‘r’ som står for *rettmaske* og ‘vr’ som står for *vrangmaske*. Listene med tall står for økende størrelser, det miste tallet i parantes står for ekstra liten og det største for ekstra stor. Strikkeren må passe på å velge tallet med samme plassnummer i hele oppskriften. Symbolet ‘M.1’ står for *Mønster 1* og og peker på et eget diagram. I diagrammet så teller strikkeren hvilken rekke de er på og følger mønsteret fra høyre mot venstre. Til slutt så er det symbolet ‘\*—\*’ som betyr gjenta symbolene mellom asteriskene et gitt antall masker.

Men hva minner dette meg om? Jo, dette er jo et programmeringsspråk. Her er det lister som blir indeksert på plassnummer. Det er *while*-løkker med som gjentar en operasjon inntil et vilkår er oppfylt. Og mønsteret det refereres til er en funksjon som tar hvilken rekke strikkeren er på og gir tilbake en liste med maskesymboler for den rekken. Strikkeoppskriften er rett og slett en serie imperative, symbolske operajoner. Det er egentlig ingen vesentlig forskjell mellom strikkeopskriften over og denne en bit Python-kode

Vi kan også utrykke oppskriften visuelt som et strikkediagram. Da er en hvit rute en rettmaske og en svart rute en vrangmaske. Resultatet blir slik:
