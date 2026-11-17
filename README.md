# Sito personale di Davide Tedeschi

Sito costruito con il tema [Academic Pages](https://github.com/academicpages/academicpages.github.io) e pubblicato gratis con GitHub Pages. Ogni modifica salvata su GitHub aggiorna il sito da sola in un paio di minuti.

## Dove si modifica cosa

| Cosa | File |
|---|---|
| Nome, ruolo, email, link a ORCID / Google Scholar nella barra laterale | `_config.yml`, sezione `author` |
| Foto | sostituisci `images/profile.png` (immagine quadrata) |
| Pagina principale (About me, ricerca, percorso, progetti, news) | `_pages/about.md` |
| Pagina del laboratorio | `_pages/lab.md` |
| Voci del menu in alto | `_data/navigation.yml` |
| Pubblicazioni | un file per articolo in `_publications/` |
| Talk | un file per talk in `_talks/` |
| Didattica | un file per corso in `_teaching/` |

## Aggiungere una pubblicazione

Copia uno dei file in `_publications/`, rinominalo con la data e un titolo breve (es. `2027-01-15-titolo-breve.md`) e cambia i campi `title`, `date`, `venue`, `citation` e `permalink`. Per i libri usa `category: books`, per gli articoli `category: manuscripts`.
