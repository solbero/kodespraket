---
layout: post
title: Strikking er programmering
---

Strikking er inn om dagen. Bestemor strikker, madammen strikker og jeg strikker. Men for å strikke noe i det hele tatt, for eksempel en genser, så må jeg ha en oppskrift. Dette er for eksempel begynnelsen på på en oppskrift for å strikke en genser:

> Legg opp (152) 168-184-200-216 m på rundp 3 1/2 og strikk 8 rekker vrangbord slik: * 2 r, 2 vr *, gjenta fra *—* til slutten av rekken. Strikk så 1 rekke og skift til rundpinne 4 og strikk 12 rekker perlestrikk slik: Rekke 1 og 2: * 1 r, 1 vr *, gjenta *—* til slutten av rekken. Rekke 3 og 4: * 1 vr, 1 r *, gjenta *—* til slutten av rekken. Genta rekke 1 til 4 til du har totalt 8 rekker.

Hvis du ikke kan lesestrikkeoppskrifter, så må nok dette fremstå som kaudervelsk. Men det er egentlig ikke så vanskelig? Symbolet ‘m’ står for *maske*, som er et «sting» i strikkearbeidet. Det er referert til to masketyper i denne oppskriften: ‘r’ som står for *rettmaske* og ‘vr’ som står for *vrangmaske*. Listen med tall i begynnelsen av oppskriften viser til økende størrelser: det miste tallet i parantes står for ekstra liten og det største tallet i slutten av listen for ekstra stor. Til slutt så er det symbolet ‘\*—\*’ som betyr gjenta symbolene mellom asteriskene til et vilkår er oppfylt.

Men hva minner dette meg om? Jo, dette er jo et programmeringsspråk! Her er det lister som blir indeksert på plassnummer. Det er *while*-løkker med som gjentar en operasjon inntil et vilkår er oppfylt. Det er primitiver som brukes for å bygge opp et komplekst mønster. Strikkeoppskriften er rett og slett en serie imperative steg som instruerer strikkeren hvilke operasjoner som skal utføres. Det er egentlig ingen vesensforskjell mellom strikkeopskriften og for eksempel en bit Python-kode.

La oss ta det hele et steg videre. Oppskriften vi har undersøkt kan også utrykkes visuelt som et strikkediagram. Da er en blank rute er en rettmaske og en svart sirkel i en rute en vrangmaske. Oppskriften blir da seende slik ut:

<figure>
    <img src="/assets/images/strikkemonster.webp " alt="Tegnet illustrasjon som viser et strikkemønster">
    <figcaption>Et strikkediagram med vrangbord i bunn og perlestrikk i topp.</figcaption>
</figure>

Men dette diagrammet ser unektelig ut som et hullkort‽ Og det er faktisk ingen tilfeldighet. De første hullkortene som ble laget ble nemlig brukt til å kontrollere veve- og strikkemaskiner. Hullene i kortene beskrev mønstret maskinen skulle produsere.

Den første maskinen som brukte hullkort til produsere et mønster ble designet av Basile Bouchon i 1725. Men bruken av hullkort til denne oppgaven tok først av på begynnelsen av 1800-tallet. Da patenterte Joseph Marie Jacquard hans Jacquard-maskin. Maskinen kunne kobles til en eksisterende vevstol og automatiserte prosessen med å veve mønster. Dette gjorde det mulig for selv en utrent vever en å veve store og kompliserte tekstilmønstere. Det gjorde det også mulig å masseprodusere mønstre, for å lage et gitt mønster trenge man kun de riktige hullkortene satt i riktig rekkefølge.

<figure>
    <img src="/assets/images/jacquard-vevstol.webp " alt="Tegnet illustrasjon som viser en Jacquard-vevstol">
    <figcaption>En Jacquard-vevstol med hullkortlenke.</figcaption>
</figure>

Ideen om at hullkort kunne brukes til å lagre intruksjoner som så kunne brukes til å «instruere» en generell regnemaskin ble først tenkt ut av Charles Babbadge. Hans _analytical engine_ skulle programmeres med hullkort. Dessverre ble maskinen ble aldri bygget og ideen med hullkort aldri utprøvd av Babbadge. Men ideen ble hentet frem igjen av Herman Hollerith i 1890. Han utviklet utviklet en maskin som brukte hullkort til å lese data. Han stiftet selskapet Tabulating Machine Company, som etter flere sammenslåinger ble til International Business Machines Corporation (IBM) i 1924. Og det er hullkortet med 80 kolonner fra IBM som de fleste ser for seg når de tenker på et hullkort.

<figure>
    <img src="/assets/images/ibm-hullkort.webp " alt="Tegnet illustrasjon som viser et IBM-hullkort">
    <figcaption>Et IBM-hullkort med 80 kolonner.</figcaption>

At strikking er en form for programmering fikk jeg selv erfare en gang jeg holdt programmeringskurs for en gruppe eldre lærererinner. Vi arbeidet med blokkprogrammering og de hadde problemer med å vri hodet rundt vilkår og løkker. Litt tilfeldig kom vi innpå temaet strikking og strikkeoppskrifter. Jeg penkte på at operasjonene vi prøvde å intruere datamaskinenen til å gjøre kjente de godt til fra fra strikking. Da var det som om det gikk opp et lys for lærerinnene. Det vi gjorde på datamaskinen var bare digital strikking. Resten av kurset gikk som en lek.
