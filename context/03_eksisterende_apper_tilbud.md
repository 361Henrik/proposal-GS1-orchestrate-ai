# GS1 Norway — eksisterende AI-apper (kontekst for fluency-tilbudet)

Dette dokumentet oppsummerer de tre webapplikasjonene Henrik allerede har
tilbudt / bygget for GS1 Norway. De er **bevis** på at GS1 allerede bygger
styrte AI-flyter (ikke "AI-turisme") — og de er konteksten fluency-tilbudet
løfter menneskene til å bruke godt.

Kilde: tre Google Docs-tilbud (Dynamisk Brief, InfoHub, Publishing).

---

## Kjeden: Brief → InfoHub → Publishing

En sammenhengende innholdsproduksjonsflyt. Hver app industrialiserer ett
tidligere ad-hoc-ledd mellom fagperson og kommunikasjonsteam.

| App | Hva den løser | Inn | Ut |
|-----|---------------|-----|-----|
| **Dynamisk Brief** | Fagpersoner mangler verktøy for å bestille kommunikasjonsinnhold; lange e-postutvekslinger og uklare bestillinger | Tema + kildemateriale + rammer | Komplett, kvalitetssikret brief |
| **InfoHub** | Tidkrevende kilde-research; lese omfattende materiale, finne hovedpoeng, faktasjekke | Godkjent brief + URL-er/PDF-er | Strukturert, sporbar innsiktspakke |
| **Publishing** | "Blanke ark-syndromet"; transformere innsikt til faktiske budskap | Brief + InfoHub-pakke + mal/kanal | Publiseringsklar tekst (.docx) |

---

## Dynamisk Brief V1.0

**Til:** GS1 Norway v/Anders · **Fra:** Henrik C. Høst (2025-10-08)

Webapplikasjon som bruker AI til å hjelpe fagpersoner lage komplette,
kvalitetssikrede briefer. Kombinerer strukturert dialog med intelligent
oppfølging.

**Slik fungerer det:** Fagperson starter brief og velger tema (GLN, GTIN,
Sporbarhet) → laster opp kildemateriale → definerer rammer (målgruppe, mål,
kanaler, tone, leveranse) → guidet AI-dialog med oppfølgingsspørsmål →
"Clarify & Confirm" der AI bekrefter hvert svar → ferdig brief genereres.

**Sentral mekanisme:** *Clarify & Confirm* — AI går inn i bekreftelsesdialog
etter hvert svar for å kvalitetssikre forståelsen før briefen ferdigstilles.

**Teknisk:** Moderne front/back-end uten omfattende koding. OpenAI GPT +
Anthropic Claude via sikre API-er. Modulær for vekst og integrasjon med
InfoHub/Publishing. **All kildekode eies av GS1 Norway.**

**Pris:** Fase 1 kartlegging kr 2 500/time (1–2 uker) · Fase 2 utvikling
kr 45 000–55 000 (6–8 uker) · Fase 3 drift kr 3 000/mnd + AI-kost
~kr 0,50–1,00/brief.

---

## InfoHub V1.0

**Til:** GS1 Norway v/Anders (2026-02-10)

Automatiserer kilde-research-fasen *etter* at en brief er godkjent.
Identifisert som tydelig utfordring på workshopen 30. oktober 2025 med
kommunikasjonsteamet. Mer enn et sammendragsverktøy — en "brief-styrt" motor
som henter relevant info for det formålet briefen definerer. Gir samme
resultat hver gang (i motsetning til ad-hoc GPT-prompting).

**Slik fungerer det:** Tar utgangspunkt i godkjent brief (vet hva den leter
etter) → bruker laster inn URL-er/PDF-er (opptil 10 i v1) → definert
prosess/templat henter ut innsikt og data → samler alt i en strukturert
"pakke" klar for produksjon, med full kildehenvisning for faktasjekk.

**v1 inkluderer:** brief-integrasjon, kildehåndtering (PDF + URL, ikke Word),
strukturerte gjenbrukbare innsiktsdokumenter, søkbart bibliotek, eksport til
PDF/Word.

**Pris:** Kartlegging kr 7 500–12 500 · Utvikling kr 55 000–65 000 (~4 uker) ·
Drift kr 3 000/mnd + ~kr 10–20/kjøring. Opptil 4 brukere + 1 admin.

---

## Publishing V1.0

**Til:** GS1 Norway v/Anders (2026-02-11)

Der kommunikasjonsmedarbeideren skaper mest verdi: transformerer innsikt til
faktiske budskap. Kobler produksjon direkte til brief og kildegrunnlag —
fjerner "blanke ark-syndromet".

**v1 er:** tekstbasert (ikke bilde/video/lyd), mal- og regelstyrt,
human-in-the-loop (AI akselererer utkast, fagperson har full redaksjonell
kontroll).

**Slik fungerer det:** Innlogging → velg godkjent brief + InfoHub-dokument
(låses som produksjonsgrunnlag) → velg leveranse (artikkel, LinkedIn,
nyhetsbrev, webinar) → velg mal/innstillinger (lengde, struktur, tone of
voice per kanal) → generer flere tekstvarianter → redaksjonell gjennomgang →
eksport til .docx eller clipboard → lagret publiseringsløp med full sporbarhet.

**v1 inkluderer:** sikker tilgang, kanal-/malbibliotek, tone-of-voice-regler,
"klar-for-publisering"-sjekk (lettvekts SEO/lesbarhet + påstandssjekk mot
kilder), eksport, opplæring.

**Pris:** Kartlegging kr 7 500–12 500 · Utvikling kr 55 000–65 000 (~4 uker) ·
Drift kr 3 000/mnd + ~kr 20–30/publiseringsløp.

---

## Hvorfor dette er konteksten, ikke tilbudet

De tre appene viser at GS1 allerede har **styrte flyter med godkjente kilder,
logging og menneskelig kontroll** — nøyaktig det AI-strategien etterspør når
den sier organisasjonen må gå "fra AI-turisme til definerte AI-medarbeidere".

Men en app er bare så god som personen som dirigerer den. Det nye tilbudet
handler om å løfte de ~20 menneskene i GS1 fra ad-hoc ChatGPT-ping-pong til
flytende, orkestrert AI-arbeid — slik at de bruker disse appene (og alt det
andre) som en komponist, ikke en turist.
