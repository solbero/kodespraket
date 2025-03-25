---
layout: post
title: Koding på norsk, det er pyton! — Første del
image: /assets/images/demonstrasjon-for-norsk.webp
---

I jobben min som utvikler skriver og leser jeg mye engelsk. Det er nøkkelord og variabelnavn på engelsk, kodekommentarer og dokumentasjon på engelsk, samt nettpratmeldinger og e-poster på engelsk.

Men må jeg virkelig skrive og lese så mye engelsk? Hvorfor er dette et _modus operandi_ jeg har akseptert uten å stille spørsmål ved det? Hva om jeg forkaster _status quo_, setter all høflighet til side, og skriver kode på norsk? Hva er det verste som kan skje? Vel, muligens dette?

```python
# Åpne filen som inneholder værdata og skriv ut hver linje fra datafilen
filnavn = værdata.txt
with open(filnavn) as fil:
    for linje in fil:
        print(linje)
```

Hadde denne kodesnutten dukket opp i en endringsforespørsel tror jeg det er mange utviklere som hadde fått et surt oppstøt, svelgt et par ganger for å få vekk den onde smaken i munnen, og deretter gått bort og tatt en alvorsprat med opphavet.

<figure>
  <img src="/assets/images/demonstrasjon-for-norsk.webp" alt="Tegnet illustrasjon som viser en demonstrasjon hvor deltagerne holder opp plakater" />
  <figcaption>Demonstrasjon for mer bruk av norsk i programmering og kildekode.</figcaption>
</figure>

Men hvorfor opplever mange utviklere det problematisk å bruke norsk i kildekode? For er ikke programmeringsspråk egentlig en type notasjon for datamaskiner? Hvis dette er tilfelle, så burde det ikke ha noe å si hva naturlig språk jeg bruker et programmeringsspråk sammen med. Som et eksempel kan vi se til matematisk notasjon. Denne notasjonen kan sømløst brukes sammen med naturlige språk uten å skape uklang. Det er få som ville reagert på blandingen av norsk og matematikk i dette utdraget fra _Store norske leksikon_:

> Om vi har en funksjon 𝑓 : ℝ→ℝ, sier vi at «𝑓 har grensen 𝑨 når 𝑥 nærmer seg et tall 𝑎» dersom 𝑓(𝑥) kan komme vilkårlig nær 𝑨 for alle 𝑥 nær 𝑎.

Her utfyller språk og notasjon hverandre i en vakker vals. Men hvorfor blir da naturlige språk og programmeringsspråk å tråkke hvernadre på tærne hvis vi prøver noe lignende? Grunnen, mener jeg, er at programmeringsspråk ikke kan sees på som en for for notasjon. Programmeringsspråk er i dag skrevet i et naturlig språk, og dette språket er engelsk!

Ser vi på den historiske for utviklingen av programmeringsspråk så er det ikke så rart at disse språkene er på engelsk. Men dette er egentlig ikke så merkelig. Forskningen innen informatikk og utviklingen av programmeringsspråk har vært drevet fram av engelskspråkelige institusjoner og bedrifter. Utviklingen av informatikk forgikk hovedsakelig i USA. I dag er engelsk så dominerende at selv programmeringsspråk utviklet av ikke-engelsktalende personer er på engelsk. Ruby, laget av japaneren Yukihiro "Matz" Matsumoto, og Python, laget av nederlenderen Guido van Rossum, er begge på engelsk.

Slå et slag for å programmere på morsmål. Vi utviklere liker å tro at vi behersker engelsk godt, men det er ikke nødvendigvis sant. Kan kun prate av egen erfaring, men jeg som har student på engelsk privatskole og bodd i engelsktalende land i undommen kjenner at jeg forklarer meg raskere, bedre og tydligere på norsk. Og hvem har vel ikke vært i et møte der møtelederen stavrer seg frem på et gebrokkent engelsk?

Det er belegg for at vi forstår programmering bedre på morsmål. En svensk [studie](https://www.degruyter.com/document/doi/10.1515/applirev-2022-0093/html) publisert i 2023 pekte på at studenter som fikk undervisning på svensk gjorde det bedre enn de som fikk undervisning på morsmål. I studien ble litt over 2000 studenter som tok et i et introduskjonsfag i programmering enten undervist på svensk eller på engelsk. De studentene som fikk undervisning fikk flere korrekte svar på en slutttest og hadde mindre frafall.

Men vi må ikke ta det for gitt at programmeringsspråk er på engelsk. Det fantes på midten av 19-hundretallet en utfordrer til det amerikanske hegmoniet innen infomatikk, og denne ufordreren var Sovjetunionen. Historien kunne vært anderledes og Sovjetunionen kunne blitt den toneangivende lederen innen informatikk. Da hadde vi gjerne sett det som naturlig med å skrive kode på russisk med kyriliske bokstaver. Men sett at soviHadde historien vært anderlenes så kunne det kanskje vært russisk som var programmeringingens universalspråk.jetunionen hadde blitt den ledende makten innen informatikk i stedet for USA? Da hadde vi kanskje programmert på russisk i stedet for engelsk? For å se for oss hvordan dette kunne sett ut så kan vi ta utgangspunkt i programmeringsspråket Эль-76 brukt på sovijetiske Elbrus-maskiner. Den følgende kodesnutten kjør en serie kalkulasjoner med variabler og skriver ut resultatet til variabelen `c`. Hadde historien vært anderlenes så kunne det kanskje vært russisk som var programmeringingens universalspråk.

```
начало
  ф32 a := 1, b := a * 5 - 2, c;
  конст d = 1, e = 2;

  c := a + b - d - e;
  печать(c)
конец
```
Men realiteten er at programmeringsspråk er på engelsk, og vi må akeptere at å blande norsk med Java, vil høres like fælt ut som å blande fransk med tysk. Løsningen fremstår derfor klar forann oss. Selve programmeringsspråket må være på norsk!

Løsningen på problemet er helt tydelig for å møte de argumentene som blir gitt. Selve programmeringspråket må være på norsk. Men hvordan skal et norsk programmeringsspråk se ut?
