# AI-denkspoor

Interactieve lijnenkaart van de theorieën, wetten, effecten en historische doorbraken die in de Nederlandse AI-podcast [Turing Station](https://turingstation.nl) worden aangehaald door Bart Mol, Bert Slagter en Peter Slagter.

Elk idee is een station op een van vier lijnen:

- **Organisatie & verandering**: Theory of Constraints, Goodhart's Law, prikkels, sluisdeuren van productiviteit
- **Maatschappij & arbeid**: Jevons-paradox, Overton-venster, Frankfurt over bullshit, Habermas, signaalinflatie
- **Technologie & tempo**: emergentie, kostendaling per capaciteitsniveau, houdbaarheid van AI-bevindingen
- **Logica & geschiedenis**: Peters Turing Line, van Boole en Gödel tot Shannon, Wiener, Turing en Dartmouth

Per station: de kern, een beeld, hoe het in de podcast langskwam (aflevering, tijdstip en spreker) en een denkvraag.

## Gebruik

- **Lezen**: klik een station op de kaart of in de lijst.
- **Luisteren**: Denkspoor Radio leest de stations voor als gesprek tussen presentator en uitlegger, met de voorleesstem van je browser.
- **Voortgang**: per station "Nieuw voor mij", "Snap ik" of "Kan ik uitleggen", plus een eigen notitie. Op GitHub Pages wordt dit in je eigen browser bewaard.
- **NotebookLM**: de knop "Bestand voor NotebookLM" downloadt alle stations als Markdown. Ook beschikbaar als [`turing-station-denkspoor.md`](turing-station-denkspoor.md).

Oefenen met Claude (uitleg, toepassen op je werk, toetsvragen) werkt alleen in de Claude-versie van de pagina.

## Bestanden

| Bestand | Inhoud |
|---|---|
| `index.html` | De pagina. Werkt los (GitHub Pages) en als Claude-artifact. |
| `data/theories.json` | Alle stations. |
| `data/meta.json` | Laatst verwerkte aflevering, gelezen afleveringen en nog te lezen afleveringen. |
| `turing-station-denkspoor.md` | Alle stations als bron voor NotebookLM. |

## Bron en status

Gebaseerd op de transcripts van Turing Station, t/m aflevering 20. Afleveringen 2, 4, 14 en 16 t/m 19 zijn nog niet verwerkt. Stations met `"geverifieerd": false` zijn alleen via een zoekresultaat gevonden; de context in de aflevering is nog niet nagelezen.

Dit is een persoonlijk project en geen officiële uitgave van Turing Station.
