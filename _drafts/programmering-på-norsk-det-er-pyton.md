---
layout: post
title: Koding på norsk, det er pyton! — Første del
image: /assets/images/demonstrasjon-for-norsk.webp
---

I jobben min som utvikler skriver og leser jeg mye engelsk. Det er nøkkelord og variabelnavn på engelsk, kodekommentarer og dokumentasjon på engelsk, samt nettpratmeldinger og e-poster på engelsk.

Men må jeg egentlig å skrive så mye på engelsk? Er egentlig ikke programmeringsspråk selvstendige språk, med eget vokabular, grammatikk og syntaks? I tillegg er mange deler av programmeringsspråk modelert på matematisk notasjon. De deler symboler, notasjon og uttrykk. Matematisk notasjon kan sømløst brukes sammen med naturlige språk, for eksempel norsk, som vist i dette utdraget fra _Store norske leksikon_ om grenser:

> Om vi har en funksjon 𝑓 : ℝ→ℝ, sier vi at «𝑓 har grensen 𝑨 når 𝑥 nærmer seg et tall 𝑎» dersom 𝑓(𝑥) kan komme vilkårlig nær 𝑨 for alle 𝑥 nær 𝑎.

Notasjonen er matematisk, ordene er på norsk. Fra dette følger det at jeg brude kunne gjøre noe tilsvarende i programmeringsspråk, hvis de er selvstendige språk. Så denne biten med Python-kode burde være uproblematisk:

Mitt inntrykk er at det er veldig mange utviklerer som får sure oppstøt hvis de ser norsk i kildekode. Hvis jeg hadde hatt følgende variabeltildeling

```python
# Åpne filen som inneholder værdata og skriv ut hver linje fra filen
filnavn = værdata.txt
with open(filnavn) as fil:
    for linje in fil:
        print(linje)
```

Hadde jeg prøvd å skive kode som det over i kodebasene som jeg jobber på så hadde det for blitt friksjon mellom meg og mine kollegaer og fort blitt hett.

Dette betyr at programmeringsspråk ikke er et eget språk, men er krevet på et språk og dette språket er engelsk! Peker på historien til utviklingen av informatikk. Engelsk er dominerende, moderne språk utviklet av enkeltpersomer som er ikke-engelsktalende er på engelsk, ref Ruby og Python. Viktig å huske på at det kunne vært anderledes. Språkene brukt i Sovjet var på russiks med kyrlliske alfabetet. Hadde historien vært anderlenes så kunne det kanskje vært russisk som var programmeringingens universalspråk.

Men dette er egentlig ikke så merkelig. Forskningen innen informatikk og utviklingen av programmeringsspråk har vært drevet fram av engelskspråkelige institusjoner og bedrifter. Men sett at sovijetunionen hadde blitt den ledende makten innen informatikk i stedet for USA? Da hadde vi kanskje programmert på russisk i stedet for engelsk? For å se for oss hvordan dette kunne sett ut så kan vi ta utgangspunkt i programmeringsspråket Эль-76 brukt på sovijetiske Elbrus-maskiner. Den følgende kodesnutten kjør en serie kalkulasjoner med variabler og skriver ut resultatet til variabelen `c`.

```
начало
  ф32 a := 1, b := a * 5 - 2, c;
  конст d = 1, e = 2;

  c := a + b - d - e;
  печать(c)
конец
```

Slå et slag for å programmere på morsmål. Vi utviklere liker å tro at vi behersker engelsk godt, men det er ikke nødvendigvis sant. Kan kun prate av egen erfaring, men jeg som har student på engelsk privatskole og bodd i engelsktalende land i undommen kjenner at jeg forklarer meg raskere, bedre og tydligere på norsk. Og hvem har vel ikke vært i et møte der møtelederen stavrer seg frem på et gebrokkent engelsk?

Det er belegg for at vi forstår programmering bedre på morsmål. En svensk [studie](https://www.degruyter.com/document/doi/10.1515/applirev-2022-0093/html) publisert i 2023 pekte på at studenter som fikk undervisning på svensk gjorde det bedre enn de som fikk undervisning på morsmål. I studien ble litt over 2000 studenter som tok et i et introduskjonsfag i programmering enten undervist på svensk eller på engelsk. De studentene som fikk undervisning fikk flere korrekte svar på en slutttest og hadde mindre frafall.

<figure>
  <img src="/assets/images/demonstrasjon-for-norsk.webp" alt="Tegnet illustrasjon som viser en demonstrasjon hvor deltagerne holder opp plakater" />
  <figcaption>Demonstrasjon for mer bruk av norsk i programmering og kildekode.</figcaption>
</figure>

Løsningen på problemet er helt tydelig for å møte de argumentene som blir gitt. Selve programmeringspråket må være på norsk. Men hvordan skal et norsk programmeringsspråk se ut?

<dl>
<dt>Bruk norske ord, med mindre det engelske ordet er blitt et låneord</dt>
<dd markdown="1">
Et mål med å et norsk programmeringsspråk må være at flest mulig handlinger

Datatypen _integer_, ofte forkortet _int_, er et engelsk ord som ikke er blitt et låneord, selv om det til en viss grad er blitt innarbeidet som begrep i infomatikk. Tallmengden __Z__, som ordet _integer_ peker, er heltallene. Typen bør da hete heltall i et norsk programmeringspråk. Dette kodeeksempelet fra Go `var number int32 = 2147483647` ville blitt `var tall heltall32 = 2147483647`.

Streng er innarbeidet på norsk som et låneord i programmering og i matematikken. Det er ikke hensiksmessig å kalle denne datatypen for en tegnkjede.
</dd>

<dt>Støtte norske bokstaver</dt>
<dd markdown="1">
Som en følge av puntket over, så må boksavene Æ, Ø og Å være støttet i tegnettet som brukes av programmeringsspråket. Det skal ikke være nødvendig å skrive AE, OE og AA. I praksis betyr det at programmeringspråket bruker Unicode som tegnsett. Hvis du vil ha `blåbørsyltetøy` som et variabelnavn så skal det være greit.
</dd>

<dt>Korte verb bøyd i imperativ for handlinger</dt>
<dd markdown="1">
Et eksempel fra C er funksjonen `fork()` som starter en ny prosess. Ordet _fork_ i betydningen ‘dele seg’ oversettes på norsk til _forgrene_. Men denne oversettelsen mener jeg blir for lang og krongelete. I imperativform har ordet _forgren_ to stavelser og syv bokstaver, ordet _fork_ har kun én stavelse og fire bokstaver. En bedre oversettelse mener jeg er ordet _skille_ med imperativform _skill_. Både _fork_ og _skille_ deler tankeinnhold, de betegner noe i verden som var én, men nå er blitt to. Et eksempel er _a fork in the road_ ‘et veiskille’.
</dd>

<dt>Korte substantiver for ting, samskriv når du skal</dt>
<dd markdown="1">
Bruk samskriving når dette er riktig. I norsk så samskriver vi substantiver, til forskjell fra engelsk. Samskriving tydligjør også hva som er data og hva som er oprasjoner. Foreksempel så vil en `.csv`-fil med bildata bli lastet inn som variabelen `bildata` og ikke `car_data` som på engelsk. Hvis denne listen blir filtert så blir det norske variabelnavnet `filtert_bildata` og ikke `filtered_car_data`. Dette gjør det tydelig hva som er data, og hva som er operasjoner. Ved å legge flere opreasjoner ville det blitt `reversert_sortert_filtert_bildata` som er veldig veldig lebard, og det er også tydlig hvilken rekkefølge operasjonene ble gjort i. Et mer innfløkt eksempel kan være `bilforhandlermatrise` som ville blitt `car_dealership_matrix` på engelsk.

Bruker understrek for mellomrom, og ikke _camelCase_ eller _PascalCase_.
</dd>

<dt>Matematikk er matematikk, det er et eget språk</dt>
<dd markdown=1>
Symboler og utrykk som kommer fra matematikken trenger ikke å oversettes. Det e rikke nødvendig å oversette matematiske operatorer til norsk. Tegnet `/` er dele, det skal ikke byttes ut med et norskt nøkkelord som `dele`. `10 / 2 = 5` er et korrekt utrykk og ikke `10 del 2 erlik 5` skal skrives slik og ikke som minus. `1 + 1` er riktig, og skal ikke skrives ut på norsk som `en pluss en`
</dd>
</dl>
