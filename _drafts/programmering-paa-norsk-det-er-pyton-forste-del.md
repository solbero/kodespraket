---
layout: post
title: Koding på norsk, det er pyton! — Første del
image: /assets/images/demonstrasjon-for-norsk.webp
---

I jobben min som utvikler skriver og leser jeg mye engelsk. Det er nøkkelord og variabelnavn på engelsk, kodekommentarer og dokumentasjon på engelsk, nettpratmeldinger og e-poster på engelsk.

Men må jeg virkelig skrive og lese så mye engelsk? Dette er et _modus operandi_ jeg har akseptert uten å stille spørsmål ved det. Hva om jeg forkaster _status quo_, setter all høflighet til side, og skriver kode på norsk? Hva er det verste som kan skje? Vel, muligens dette…

```python
# Åpne filen som inneholder værdata og skriv ut hver linje fra datafilen
filnavn = værdata.txt
with open(filnavn) as fil:
    for linje in fil:
        print(linje)
```

Hadde denne kodesnutten dukket opp i en endringsforespørsel tror mange utviklere hadde fått et surt oppstøt. Etter å ha svelget et par ganger, for å få vekk den vonde smaken i munnen, ville de fleste gått sporenstreks bort til opphavet av koden og tatt en alvorsprat.

Men hvorfor opplever mange utviklere det problematisk å bruke norsk i kildekode? For er ikke programmeringsspråk egentlig en type notasjon for datamaskiner? Hvis dette er tilfelle, så burde det ikke ha noe å si hva språk jeg bruker sammen med et programmeringsspråk. Matematisk notasjon, for eksempel, kan sømløst brukes sammen med et naturlig språk uten å skape ulyd. Det er få som ville reagert på blandingen av norsk og matematisk notasjon i dette utdraget fra _Store norske leksikon_:

> Om vi har en funksjon 𝑓 : ℝ→ℝ, sier vi at «𝑓 har grensen 𝑨 når 𝑥 nærmer seg et tall 𝑎» dersom 𝑓(𝑥) kan komme vilkårlig nær 𝑨 for alle 𝑥 nær 𝑎.

Her utfyller språk og notasjon hverandre i en vakker vals. Hvorfor opplever vi da at norsk og programmeringsspråk blir å tråkke hverandre på tærne hvis vi prøver å sette dem sammen på samme vis? Grunnen, mener jeg, er at programmeringsspråk ikke er en form for notasjon eller et eget datamaskinspråk. Programmeringsspråk er faktisk skrevet på et naturlig språk og dette språket er engelsk!

Ser vi på den historiske utviklingen til moderne programmeringsspråk så er den engelske dominansen ikke så merkelig. Det var engelskspråkelige institusjoner og bedrifter, i hovedsak fra USA, som drev utviklingen og forskningen innen fagfeltet informatikk. I dag er engelsk så dominerende at selv programmeringsspråk utviklet av ikke-engelsktalende personer er på engelsk. Ruby, laget av japaneren Yukihiro "Matz" Matsumoto, og Python, laget av nederlenderen Guido van Rossum, er begge på engelsk.

Vi utviklere liker å tro at vi behersker engelsk godt, både skriftlig og muntlig, men det er ikke nødvendigvis rett. Jeg tror vi utviklere, når vi vurderer våre engelskferdigheter, lider av eksponeringsbias. Det betyr at vi tror vi er bedre til engelsk enn vi egentlig er, og grunnen til at vi tror dette er fordi at vi er blitt så mye eksponert for det engelske språket.

<figure>
  <img src="/assets/images/demonstrasjon-for-norsk.webp" alt="Tegnet illustrasjon som viser en demonstrasjon hvor deltagerne holder opp plakater" />
  <figcaption>Demonstrasjon for mer bruk av norsk i programmeringspråk og kildekode.</figcaption>
</figure>

Mye tyder på at vi forstår programmering bedre på morsmål enn på engelsk. En svensk [studie](https://www.degruyter.com/document/doi/10.1515/applirev-2022-0093/html), publisert i 2023, gir belegg for denne påstanden. I studien ble litt over 2000 svenske studenter, som tok et introduksjonsfag i programmering, tilfeldig plassert i én av to grupper: en gruppe hvor pensum var på svensk og en gruppe hvor pensum var på engelsk. Studentene som fikk pensum på svensk gjorde det bedre på en avsluttende prøve i faget sammenlignet med de studentene som fikk pensum på engelsk. I tillegg hadde svenske gruppen førre frafall sammenlignet med den engelske gruppen.

Med andre ord, det er mye som tyder på at å kode mer på norsk kan gi positive effekter. Men selv om utviklere blir presentert for disse gode argumentene, så tror jeg de fleste fortsatt vil foretrekke å skrive kode på engelsk. Jeg blir i hvert fall å fortsette å skrive koden min på engelsk. Grunnen til det er at å blande norsk og for eksempel Java i samme kodelinje er like fælt som å blande fransk og tysk i samme setning.

Men hvordan skal det da bli mer norsk i kildekode, hvis ikke engang jeg har lyst til å blande norsk og et engelsk i min egen kildekode? Det eksisterer faktisk kun én løsning på dette problemet: selve programmeringsspråket må være på norsk!

I andre del av denne artikkelen vil jeg designe og implementere et norsk programmeringsspråk! Det er bare å begynne å glede, grue eller gruglede seg.
