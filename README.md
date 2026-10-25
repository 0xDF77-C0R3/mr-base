# marco-rocchi.it

Sito di Marco Rocchi, Rettore dell'Università di Urbino Carlo Bo per il sessennio 2026-2032.
Nato come sito della campagna elettorale, reindirizza ora verso la pagina istituzionale ufficiale su UniUrb (`https://www.uniurb.it/persone/marco-rocchi`).

## Struttura

- `index.html` — pagina di reindirizzamento (meta refresh + JavaScript + fallback link)
- `404.html` — gestore delle pagine non trovate su GitHub Pages, con reindirizzamento identico
- `Programma-*.pdf` — il programma elettorale, versione completa e sintesi
- `gource-*.mp4` — la storia del repository in video (orizzontale e verticale)
- `Materiali-e-bozze/` — sorgenti delle immagini e bozze storiche

## Pubblicazione

Ogni push su `main` pubblica il sito su GitHub Pages tramite
`.github/workflows/static.yml`; il dominio è impostato in `CNAME`.
Per provare le modifiche in anteprima si usa una copia `Test.html` con `noindex`,
da riportare poi in `index.html`.

## Licenza

MIT, vedi `LICENSE`.
