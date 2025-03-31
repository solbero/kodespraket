---
layout: post
title: Koding på norsk, det er pyton! — Første del
image: /assets/images/demonstrasjon-for-norsk.webp
---

I jobben min som utvikler skriver og leser jeg mye engelsk. Det er nøkkelord og variabelnavn på engelsk, kodekommentarer og dokumentasjon på engelsk, samt nettpratmeldinger og e-poster på engelsk.

Men må jeg virkelig skrive og lese så mye engelsk? Dette et _modus operandi_ jeg har akseptert uten å stille spørsmål ved det. Hva om jeg forkaster _status quo_, setter all høflighet til side, og skriver kode på norsk? Hva er det verste som kan skje? Vel, muligens dette…

```python
# Åpne filen som inneholder værdata og skriv ut hver linje fra datafilen
filnavn = værdata.txt
with open(filnavn) as fil:
    for linje in fil:
        print(linje)
```

Hadde denne kodesnutten dukket opp i en endringsforespørsel tror jeg det er mange utviklere som hadde fått et surt oppstøt, svelgt et par ganger for å få vekk den onde smaken i munnen og deretter gått bort og tatt en alvorsprat med opphavet til koden.


Men hvorfor opplever mange utviklere det problematisk å bruke norsk i kildekode? For er ikke programmeringsspråk egentlig en type notasjon for datamaskiner? Hvis dette er tilfelle, så burde det ikke ha noe å si hva naturlig språk jeg bruker sammen med et programmeringsspråk. Matematisk notasjon, for eksempel, kan sømløst brukes sammen med et naturlige språk uten å skape uklang. Det er få som ville reagert på blandingen av norsk og matematematisk notasjon i dette utdraget fra _Store norske leksikon_:

> Om vi har en funksjon 𝑓 : ℝ→ℝ, sier vi at «𝑓 har grensen 𝑨 når 𝑥 nærmer seg et tall 𝑎» dersom 𝑓(𝑥) kan komme vilkårlig nær 𝑨 for alle 𝑥 nær 𝑎.

Her utfyller språk og notasjon hverandre i en vakker vals. Men hvorfor opplever vi da at naturlige språk og programmeringsspråk blir å tråkke hverandre på tærne hvis vi prøver å sette dem sammen? Grunnen, mener jeg, er at programmeringsspråk ikke er en form for notasjon eller et eget språk. Programmeringsspråk er faktisk skrevet på et naturlig språk, og dette språket er engelsk!

<figure>
  <img src="/assets/images/demonstrasjon-for-norsk.webp" alt="Tegnet illustrasjon som viser en demonstrasjon hvor deltagerne holder opp plakater" />
  <figcaption>Demonstrasjon for mer bruk av norsk i programmeringspråk og kildekode.</figcaption>
</figure>

Ser vi på den historiske utviklingen til moderne programmeringsspråk så er den engelske dominansen egentlig ikke så merkelig. Det er engelskspråkelige institusjoner og bedrifter, i hovedsak fra USA, som har drevet utviklingen av, og forskningen innen infomatikk. I dag er engelsk så dominerende innen fagfeltet at selv programmeringsspråk utviklet av ikke-engelsktalende personer er på engelsk. Ruby, laget av japaneren Yukihiro "Matz" Matsumoto, og Python, laget av nederlenderen Guido van Rossum, er begge på engelsk.

Men historien kunne vært anderledes. På midten av 19-hundretallet eksisternte det en nasjon som utfordret USA på mange områder, nemlig Sovjetunionen. Hvis Sovjetunionen hadde blitt den toneangivende lederen innen informatikk, så hadde vi utviklere sett det som like naturlig å skrive kode på russik som vi i dag skriver kode på engelsk. Da hadde dette kodeeksempelet, i programmeringsspråket Эль-76, oppleves som helt naturlig.

```
начало
  ф32 a := 1, b := a * 5 - 2, c;
  конст d = 1, e = 2;

  c := a + b - d - e;
  печать(c)
конец
```

Vi utviklere liker å tro at vi behersker engelsk godt, men det er ikke nødvendigvis sant. Her lider nok vi utviklere av eksponeringsbias, som betyr at vi tror vi er bedre til noe enn vi egentlig er fordi at vi er blitt så mye ekspornert for det. Vi forstår faktisk ting bedre på morsmål enn på engelsk. En svensk [studie](https://www.degruyter.com/document/doi/10.1515/applirev-2022-0093/html), publisert i 2023, gir belegg for denne påstanden. I studien ble litt over 2000 svenske studenter, som tok et introduksjonsfag i programmering, tilfeldig plassert i én av to grupper: i den ene gruppen ble pensum gitt på svensk, i den andre ble det gitt på engelsk. Studentene som fikk pensum på engelsk gjorde det bedre på en avsluttende prøve i faget sammelinget med de studentene som fikk pensum på engelsk. Den svenske gruppen hadde også mindre frafall sammelinget med den engelske gruppen.

Men selv gitt slike bevis så vil dagen utviklere foretrekke å skrive på engelsk så lange moderne programmeringsspråk er på engelsk. Å blande norsk og Java vil oppleves som like uforenelig som å blande tysk og fransk. Gitt denne realiteten så står det tilbake kun én løsning. Selve programmeringsspråket må være på norsk! Men hvordan skal et norsk programmeringsspråk se ut? For å finne ut av det må du vente i spenning på andre del av denne artikkelserien der jeg blir å designe og lage et programmeringsspråk på norsk.
