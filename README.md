# Sito di Samuel Garbarino

Sito statico in HTML e Sass con Bootstrap 5.3, senza JavaScript.

## Compilare il CSS
```
pnpm install
pnpm build     # una volta
pnpm watch     # ricompila a ogni modifica
```
I sorgenti sono in `assets/sass/`, il risultato in `assets/css/style.css` (va versionato: GitHub Pages non compila).

## Note
- La chiave di Web3Forms in `contattami/index.html` è pubblica per progetto (consente solo di inviare messaggi alla casella di Samuel). Per cambiarla si genera una nuova chiave su web3forms.com.
- Se l'URL del sito non è `https://samuelgarbarino.github.io/sito-html-css/`, aggiornalo in canonical, og:url, og:image, sitemap, robots, JSON-LD, `404.html` e nel campo `redirect` del form.

## Pubblicare
Repository pubblico su GitHub, Settings, Pages, ramo `main`, cartella `/ (root)` (il contenuto di `05-sito/` è la radice del repository).
