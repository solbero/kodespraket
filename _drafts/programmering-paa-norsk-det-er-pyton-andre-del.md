Men vi må huske på at historien kunne vært anderledes. På midten av nittenhundretallet eksisterte det en nasjon som utfordret USA på mange områder, også innen informatikk. Denne nasjonen var Sovjetunionen. Hvis Sovjetunionen hadde blitt den toneangivende lederen innen utvilkingen av programmeringsspråk, så hadde nok vi utviklere sett det som like naturlig å skrive kode på russisk som vi i dag skriver kode på engelsk. Da hadde dette kodeeksempelet, i programmeringsspråket Эль-76, oppleves som helt naturlig.

```
начало
  ф32 a := 1, b := a * 5 - 2, c;
  конст d = 1, e = 2;

  c := a + b - d - e;
  печать(c)
конец
```

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

<dt>Substantiver for ting, samskriv når du kan</dt>
<dd markdown="1">
En av superkreftene til norsk er at vi kan sammenskrive substantiv. Vi kan skrive ord som _utenriksdepartementsrapport_ hvis engelsktalende må skrive _report by the ministry of foreign affairs_.
Bruk samskriving når dette er riktig. I norsk så samskriver vi substantiver, til forskjell fra engelsk. Samskriving tydligjør også hva som er data og hva som er oprasjoner. Foreksempel så vil en `.csv`-fil med bildata bli lastet inn som variabelen `bildata` og ikke `car_data` som på engelsk. Hvis denne listen blir filtert så blir det norske variabelnavnet `filtert_bildata` og ikke `filtered_car_data`. Dette gjør det tydelig hva som er data, og hva som er operasjoner. Ved å legge flere opreasjoner ville det blitt `reversert_sortert_filtert_bildata` som er veldig veldig lebard, og det er også tydlig hvilken rekkefølge operasjonene ble gjort i. Et mer innfløkt eksempel kan være `bilforhandlermatrise` som ville blitt `car_dealership_matrix` på engelsk.

Bruker understrek for mellomrom, og ikke _camelCase_ eller _PascalCase_.
</dd>

<dt>Matematikk er matematikk, det er et eget språk</dt>
<dd markdown=1>
Symboler og utrykk som kommer fra matematikken trenger ikke å oversettes. Det e rikke nødvendig å oversette matematiske operatorer til norsk. Tegnet `/` er dele, det skal ikke byttes ut med et norskt nøkkelord som `dele`. `10 / 2 = 5` er et korrekt utrykk og ikke `10 del 2 erlik 5` skal skrives slik og ikke som minus. `1 + 1` er riktig, og skal ikke skrives ut på norsk som `en pluss en`
</dd>
</dl>
