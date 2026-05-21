# GS1 Norway — AI-fluency tilbud (ThreeSixtyOne)

Prosjektmappe for tilbudet til GS1 Norway. Kjernen: en nettside (ikke
innlogging — unik delbar URL) som presenterer fluency-tilbudet, lett å
oppdatere og endre raskt.

## Hva dette tilbudet er

Å løfte GS1s ~20 ansatte fra ad-hoc ChatGPT-ping-pong til flytende,
orkestrert AI-arbeid — "dancing with intelligence". Menneskelaget som sitter
under og mellom de tre appene de allerede har (Dynamisk Brief → InfoHub →
Publishing).

Det er **ikke** en ny app. Appene er kontekst og bevis på at GS1 allerede
bygger styrte flyter; tilbudet gjør menneskene i stand til å dirigere dem.

## Mappestruktur

```
gs1-norway/
├── README.md                  ← du er her
├── context/                   ← last opp som Claude Project-kontekst
│   ├── 00_strategisk_syntese_brief.md     ★ start her — kobler strategi til metodikk
│   ├── 01_Vision2030_Strategidokument_styret.docx
│   ├── 02_GS1_AI_innspill_Vision2030.docx
│   └── 03_eksisterende_apper_tilbud.md    (Brief/InfoHub/Publishing)
├── offer/                     ← tilbudstekst / pris / e-postutkast
├── site/                      ← nettsiden (index.html) — det som deles med GS1
└── assets/                    ← bilder, logo, ev. skjermbilder av appene
```

## Arbeidsflyt

1. **Kontekst er kilden.** `context/00_strategisk_syntese_brief.md` inneholder
   GS1s egne ord som skal speiles tilbake. Les den før noe skrives.
2. **Bygg/oppdater nettsiden** i `site/index.html`.
3. **Del via unik URL** (se `site/README.md` for deploy-notater).
4. **Last hele mappen opp som et Claude Project** — da har Claude all kontekst
   når du itererer på tilbud eller nettside senere.

## Kjernekontakt

GS1 Norway v/Anders. Henrik C. Høst · henrik@threesixty1.com ·
www.threesixtyone.ai · 941 52 361
