---
layout: post
title: Strikking er programmering
---

Strikking er inn om dagen. Bestemor strikker, madammen strikker, og jeg strikker. Men for å strikke noe i det hele tatt så må jeg ha en oppskrift. Under ser du for eksempel begynnelsen til en oppskrift for å strikke en genser:

> Legg opp (152)-168-(184)-200-(216) m på rundp 3,5 og strikk 8 omg vrangbord slik: \* 2 r, 2 vr \*, gjenta fra \*—\* til slutten av omg. Strikk 1 omg r. Bytt til rundp 4 og strikk 12 omg perlestrikk slik: Omg 1 og 2: \* 1 r, 1 vr \*, gjenta fra \*—\* til slutten av omg. Omg 3 og 4: \* 1 vr, 1 r \*, gjenta fra \*—\* til slutten av omg. Genta omg 1 til 4 til du har totalt 8 omg perlestrikk.

Hvis du ikke kan lese strikkeoppskrifter, så må nok dette fremstå som kaudervelsk. Men det er egentlig så vanskelig? Bokstaven ‘m’ står for *maske*, som er en garnløkke i strikkearbeidet. Det er referert til to masketyper i denne oppskriften: ‘r’ som står for *rettmaske* og ‘vr’ som står for *vrangmaske*. Det er andre forkortelser i oppskriften: ‘p‘ for _pinne_ og ‘omg’ for _omgang_. Listen med tall i begynnelsen av oppskriften viser til økende størrelser: det miste tallet står for ekstra liten og det største tallet for ekstra stor.  Til slutt så er det symbolet ‘\*—\*’ som betyr gjenta symbolene mellom asteriskene til et vilkår er oppfylt.

Men hva minner dette meg om? Jo, dette er jo et programmeringsspråk! Her er det lister som blir indeksert på plassnummer. Det er *while*-løkker som gjentar en operasjon inntil et vilkår er oppfylt. Det er primitiver som brukes for å bygge opp et komplekst mønster. Strikkeoppskriften er rett og slett en serie imperative steg som instruerer strikkeren hvilke operasjoner som skal utføres. Det er egentlig ingen vesensforskjell mellom strikkeopskriften og for eksempel en bit Python-kode.

La oss ta det hele et steg videre. Oppskriften vi har undersøkt kan også utrykkes visuelt som et strikkediagram. Da er en blank rute er en rettmaske og en svart sirkel i en rute en vrangmaske. Oppskriften blir da seende slik ut:

<figure>
    <img src="/assets/images/strikkemonster.webp " alt="Tegnet illustrasjon som viser et strikkemønster">
    <figcaption>Et strikkediagram med vrangbord i bunn og perlestrikk i topp.</figcaption>
</figure>

Dette diagrammet ser unektelig ut som et hullkort, ikke sant‽ Og det er faktisk ingen tilfeldighet. De første hullkortene som ble laget tidlig på 1700-tallet ble nemlig brukt til å kontrollere veve- og strikkemaskiner. Hullene i, og skekvensen av, kortene beskrev mønstret maskinen skulle produsere. Men bruken av hullkort til denne oppgaven tok først av på begynnelsen av 1800-tallet. Da patenterte Joseph Marie Jacquard sin Jacquard-maskin. Maskinen kunne kobles til en eksisterende vevstol og automatiserte prosessen med å veve mønster. Dette gjorde det mulig for selv en utrent vever å veve store og kompliserte tekstiler.

<figure>
    <img src="/assets/images/jacquard-vevstol.webp " alt="Tegnet illustrasjon som viser en Jacquard-vevstol">
    <figcaption>En Jacquard-vevstol med hullkortlenke.</figcaption>
</figure>

Charles Babbadge videreutviklet ideen om at hullkort kunne brukes til å lagre intruksjoner og data som kunne leses av en generell regnemaskin. Hans _analytical engine_, som han designet i 1837, skulle instrueres med bruk av hullkort. Men det ble med ideen for Babbadge, han fikk aldri bygget maskinen på grunn av manglende finansiering.

Ideen med å bruke hullkort til å lagre data samt å instruere en maskin fikk sitt store gjennombrudd med Herman Hollerith. Han patenterte i 1884 en maskin som kunne lese data skrevet på hullkort. Hans maskiner ble med stor suksess brukt i den amerikanske folketellingen i 1890 til å lese og prossesere innsamlet data. Noen få år etter folketellingen stiftet han, i 1896, selskapet Tabulating Machine Company. Dette delskapet ble etter flere sammenslåinger til slutt til International Business Machines Corporation (IBM) i 1924. Dette selskapet ble synonymt med datamaskiner og programmering i 1960 og 70-årene. Det er et IBM-hullkort med 80 kolonner fra denne tiden de fleste ser for seg når de tenker på et hullkort.

<figure>
    <img src="/assets/images/ibm-hullkort.webp " alt="Tegnet illustrasjon som viser et IBM-hullkort">
    <figcaption>Et IBM-hullkort med 80 kolonner.</figcaption>

At strikking er en form for programmering fikk jeg selv erfare en gang jeg holdt programmeringskurs for en gruppe eldre lærererinner. Vi arbeidet med blokkprogrammering og de hadde problemer med å vri hodet rundt hvordan vilkår og løkker fungerte. Litt tilfeldig kom vi inn på temaet strikking og strikkeoppskrifter. Jeg pekte på at operasjonene vi prøvde å instrurere datamaskinenen til å gjøre kjente de til fra strikking. Da var det som om en bryter ble skrudd på inni hodene til lærerinnene. Det vi gjorde på datamaskinen var bare «digital strikking». Det hører med til historien at etter dette så gikk resten av kurset med letthet.
