# marco-rocchi.it

Sito di Marco Rocchi, Rettore eletto dell'Università di Urbino Carlo Bo per il sessennio 2026-2032.
Nato come sito della campagna elettorale, oggi è una pagina unica.

## Struttura

- `index.html` — la pagina, HTML e CSS in un solo file, senza dipendenze di build
- `Programma-*.pdf` — il programma elettorale, versione completa e sintesi
- `gource-*.mp4` — la storia del repository in video (orizzontale e verticale)
- `Materiali-e-bozze/` — sorgenti delle immagini e bozze, non linkati dal sito

## Pubblicazione

Ogni push su `main` pubblica il sito su GitHub Pages tramite
`.github/workflows/static.yml`; il dominio è impostato in `CNAME`.
Per provare le modifiche in anteprima si usa una copia `Test.html` con `noindex`,
da riportare poi in `index.html`.

## Licenza

MIT, vedi `LICENSE`.
