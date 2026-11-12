# Sito web — Dott.ssa Silvia Zagami

## Stato della versione

- **Release approvata per la pubblicazione:** `v13.6.0`.
- **Versione precedente pubblicata:** `v13.5.1`, tag Git sul commit `07becead980a61e94304eca2ffc8f418009706d4`.
- **Stato effettivo online della nuova release:** da verificare dopo il caricamento su GitHub Pages.
- **Repository:** `willi1am/Silvia-preview`, ramo `main`, cartella `/(root)`.
- **Dominio personalizzato:** non ancora configurato. Le immagini OG usano l'URL GitHub Pages attuale.

## Cosa cambia in v13.6.0

- Copertine Open Graph 1200×630 per Home, Chi sono, Prestazioni, Contatti; Home anche per Privacy e Cookie.
- Foto originale della dottoressa e monogramma già presenti nell'identità del sito, con consenso da confermare per la pubblicazione delle nuove copertine.
- Favicon ICO/PNG, Apple touch icon, icone Android e Web App Manifest.
- Tag Open Graph e Twitter/X Card personalizzati per ogni pagina, con URL completi HTTPS.
- **Nessuna modifica ai contenuti clinici, ai recapiti e al layout visibile della v13.5.1**.

## Struttura e caricamento

La radice del repository deve contenere:

- `index.html`, `chi-sono.html`, `prestazioni.html`, `contatti.html`, `privacy.html`, `cookie.html`;
- `README.md`, `CHANGELOG.md`, `site.webmanifest`;
- la cartella **`assets/`** con tutte le immagini e icone del pacchetto.

**Non caricare lo ZIP nel repository.** Da iPad, se non riesci a caricare la cartella direttamente, crea prima la cartella `assets` da GitHub con il file `assets/.gitkeep` (incluso anche in questo archivio) e poi carica le immagini dall'interno. Carica gli HTML per ultimi.

## Collaudo prima di taggare

1. Verificare che il workflow Pages sia verde sul nuovo commit.
2. Aprire direttamente `https://willi1am.github.io/Silvia-preview/assets/og-home.jpg` e le altre tre immagini OG.
3. Verificare `index.html`, `prestazioni.html`, navigazione e icone in Safari e Chrome.
4. Provare il link in WhatsApp/Messaggi; è normale che le cache delle anteprime impieghino del tempo.
5. Solo dopo i controlli creare tag e GitHub Release `v13.6.0` sul commit pubblicato.

## Dominio personalizzato

Quando verrà acquistato, sostituire gli URL assoluti `og:url`, `og:image`, `twitter:image`, canonical (dove applicabile) e verificare il DNS/HTTPS. Questo sarà un aggiornamento separato.
