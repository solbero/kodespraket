---
layout: post
title: Metaforer i Git
image:
---

Har du noen gang tenkt over at versjonskontrollsystemet Git er proppfull av metaforer? Og at det er metaforene som gjør det mulig for utviklere å ressonnere om det abstrakte og komplekse konseptet versjonskontroll?

Jeg husker første gang jeg hørte om metaforer; det var i en norsktime i fjerde klasse. Eksempelet lærerinnen min skrev på tavlen var: «Ole er en løve». Hun forklarte oss elever at setningen ikke betød at Ole faktisk var en løve med pels og hale. I stedet var det noen egenskaper som vi knytter til løver — slik som mot, edelhet og styrke — som ble knyttet til Ole. Hun foklarte oss at metaforer er et språklig verktøy som blir brukt i tekster for å gjøre dem mer levende og interessante.

Slik forstsatte jeg å forstå metaforer frem til voksen alder. Helt til jeg leste boken _Hverdagslivets metaforer_ av George Lakoff og Mark Johnson. Den boken forandret min forståelse av metaforer og hvordan vi mennesker forstår verden rundt oss. I boken argumenterer forfatterne for at hele vår forståelse av abstrakte konsepter — slik som tid, kjærlighet eller inflasjon — bygger på konseptuelle metaforer.

I en konseptuell metafor er det alltid et kildedomene og et måldomene. Kildedomenet er et avgrenset, sammenhengende, konkret og allment erfarings- eller kunnskapsområde. Måldomenet, på den andre hånd, er et utflytende, oppdelt og abstrakt erfarings- eller kunnskapsområde. Mellom disse to domenene er det korrepondanser som gjør at vi forstår begrepene, idéene og tankene i det abstrakte måldomenet i lys av det konkrete kildedomenet.

<figure>,
  <img src="/assets/images/kilde-og-maaldomene.webp" alt="Tegnet illustrasjon som viser korrespondansen mellom et kilde- og måldomene i en kognitiv metafor">
  <figcaption>Korrespondanser mellom et kilde- og måldomene i en kognitiv metafor.</figcaption>
</figure>

Den mest fremtredene konseptuelle metaforen i Git er <span style="font-variant: small-caps;">kode er et tre</span>. Denne metaforen kommer til utrykk i kommandoer som _root_, _trunk_, _branch_, _prune_, _leaf_, _cherry-pick_ og _worktree_. I metaforen <span style="font-variant: small-caps;">kode er et tre</span> brukes de konkrete erfaringene vi mennesker har med trær, erfaringer som er gyldige over nesten hele verden, til å ressonere det abstrakte konseptet kodeendringer over tid.

En kodebase, likt et tre, vokser ut fra en rot. Den får flere grener over tid og blir mer og mer kompleks. For å skjøtte treet må det av og til beskjæres for å beholde riktig fasong. Bruken av metaforen <span style="font-variant: small-caps;">kode er et tre</span> gir utviklere et alment forståelig språk for å kunne tenke om og diskutere kodeforandringer over tid.

En vellykket kognitiv metafor har et rikt kildedomene som gjør det mulig å utvide korrespondansene mellom kilde- og måldomenet. For metaforen <span style="font-variant: small-caps;">kode er et tre</span> så kan begrepet _grafting_ ‘poding’ fra kildedomenet <span style="font-variant: small-caps;">tre</span> brukes for å gi en ny forståelse av domenet <span style="font-variant: small-caps;">kode</span>.

Poding er en botanisk teknikk der man får to foskjellige planter til å vokse sammen med den ene planten som vert for den andre. Denne idéen er kjent for utviklere i og med at vi ofte henter kode fra en kodebase og plasserer den inni en annen kodebase. I stedet for å snakke om å importere kode så kunne vi i stedet snakket om å pode inn kode — kodepoding,  rett og slett! Selv synes jeg ordet poding er et bedre ord enn importering. Grunnen til dette er at når jeg kodepoder så peker ordet på at koden jeg henter blir å gro sammen med koden jeg allerede har. Når koden først er podet, så er den vanskelig å fjerne igjen uten å skade kodebasen den nå vokser i. Dette er en dimensjon ved å hente inn kode fra andre kodebaser som ordet importere ikke fanger.

Det kjekke med kognitive metaforer er at de muligjør å bytte ut kildedomene med et annet domene som er formlikt. Metaforen <span style="font-variant: small-caps;">kode er et tre</span> kan byttes ut med metaforene <span style="font-variant: small-caps;">kode er en elv</span> eller <span style="font-variant: small-caps;">kode er et rørsystem</span> uten at korrepondansene mellom mål- og kildedomenet bryter sammen.

<figure>,
  <img src="/assets/images/metaforer.webp" alt="Tegnet illustrasjon som viser forskjellige kildedomener som kan brukes for å forstå kode">
  <figcaption>Forskjellige kildedomener som kan brukes for å forstå kodeforandringer over tid.</figcaption>
</figure>

En utvikler kunne da snakket om et ‘vassdrag’ eller et ‘rørsystem’ i stedet for et tre, en ‘sidebekk‘ eller en ‘stikkledning‘ i stedet for en gren, et ‘oppkomme’ eller en ‘pumpestasjon’ i stedet for en rot. Språklig gir disse korrespondansene god mening, selv om de nok oppleves uvante.

Så neste gang du arbeider i et objektorientert programmeringsspråk, tenk da hvor vanskelig det hadde vært å ressonere om koden uten metaforen <span style="font-variant: small-caps;">kode er en familie</span>. Eller snakke om filbehandling uten metaforen <span style="font-variant: small-caps;">data er et arkivskap</span>.

«Metaphors, actually, are all around.»
