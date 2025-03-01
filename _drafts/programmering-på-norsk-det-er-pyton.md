---
layout: post
title: Koding på norsk, det er pyton!
image:
---

I jobben min som utvikler skriver jeg mye på engelsk. Jeg skriver kode som har nøkkelord og innebygde funksjoner på engelsk, kodekommentarer på engelsk og dokumentasjon på engelsk. Men med tanke på at jeg arbeider i et team der alle kollegaene har norsk som morsmål og kunden er en norsk, offentlig etat så burde jeg egentlig i hovedsak skrive på norsk.

Men dette er egentlig ikke så merkelig. Forskningen innen informatikk og utviklingen av programmeringsspråk har vært drevet fram av engelskspråkelige institusjoner og bedrifter. Presset for at

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

<dt>Korte substantiver for ting</dt>
<dd markdown="1">
</dd>

<dt>Matematikk er matematikk, det er et eget språk</dt>
<dd markdown=1>
Symboler og utrykk som kommer fra matematikken trenger ikke å oversettes. Det e rikke nødvendig å oversette matematiske operatorer til norsk. Tegnet `/` er dele, det skal ikke byttes ut med et norskt nøkkelord som `dele`. `10 / 2 = 5` er et korrekt utrykk og ikke `10 del 2 erlik 5` skal skrives slik og ikke som minus. `1 + 1` er riktig, og skal ikke skrives ut på norsk som `en pluss en`
</dd>

</dl>

Mitt inntrykk er at det er veldig mange utviklerer som får sure oppstøt hvis de ser norsk i kildekode. Hvis jeg hadde hatt følgende variabeltildeling

```
public class Colors
{
  private readonly List<string> colors = new() {"red", "green", "blue"};

  public void List()
  {
    foreach (string color in colors)
    {
      Console.WriteLine(color);
    }
  }
}
```

```
offentlig klasse Farger
{
  privat lesebeskyttet Liste<streng> farger = ny() {"rød", "grønn", "blå"};

  offentlig tom RamsOpp()
  {
    forhver (streng farge av farger)
    {
      Konsoll.SkrivLinje(farge);
    }
  }
```
