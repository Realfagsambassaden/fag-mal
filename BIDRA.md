# Slik bidrar du – Realfagsambassaden

Takk for at du vil være med! Her er alt du trenger for å skrive et fag.

## 1. Tre måter å redigere på

| Du vil … | Gjør slik |
|---|---|
| Rette en skrivefeil raskt | Åpne fila på github.com og klikk blyanten ✏️. Skriv, og klikk **Commit changes**. |
| Skrive mye i nettleseren | Trykk **punktum (.)** på tastaturet når du er inne i repoet. Da åpnes en full editor (VS Code) i nettleseren. |
| Jobbe på egen maskin | Installer [VS Code](https://code.visualstudio.com) og [Quarto](https://quarto.org/docs/get-started/). Klon repoet (Source Control → Clone Repository). |

## 2. Mappene

```
fag.yml                  – navn, nettsted og status for faget
kapitler/
  01-forste-kapittel/
    index.qmd            – kapittelets forside
    01-eksempelside.qmd  – én side; sorteres etter filnavn
  02-neste-kapittel/ …
bilder/                  – tegninger og figurer
```

## 3. Byggeklosser

Alle eksemplene står i `kapitler/01-forste-kapittel/01-eksempelside.qmd`. Kort oppsummert:

- **Formler:** `$F = ma$` i teksten, `$$ … $$` på egen linje.
- **Video:** `{{< video https://www.youtube.com/watch?v=… >}}`
- **Bokser:** `::: {.callout-note title="Definisjon: …"}` … `:::` (også `callout-tip`, `callout-warning`) og `::: {.eksempel}`.
- **Oppgave med løsning:** `::: {.oppgave tittel="…"}` med en `::: {.losning}` inni. Studentene får «Vis løsning» og «Få et hint» (KI-hint som bruker løsningen din, så skriv gode løsninger).
- **Kjørbar Python:** en kodeblokk som starter med ` ```{.python .kjor}`.

## 4. Stil

- Én idé om gangen. Korte avsnitt, mange figurer.
- Skriv til noen som ikke kan faget fra før. Forklar *hvorfor*, ikke bare *hvordan*.
- Fysikkonstanter og enheter skrives ikke i kursiv.
- Tegninger: Dashman-stil og håndskrift fra iPad passer godt. Lagre som PNG eller WebP.

## 5. Status

Sett `status` i `fag.yml`:

- `skjult` – vises ikke på nettsiden (start her)
- `arbeid` – vises med «Under arbeid»
- `klar` – vises som ferdig fag

## 6. Rettigheter

Innholdet publiseres av Realfagsambassaden. Avklar lisens og eierskap med plattformansvarlig før du publiserer innhold du har laget i en annen jobb.

Spørsmål? Ta kontakt med plattformansvarlig.
