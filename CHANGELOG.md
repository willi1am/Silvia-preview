# CHANGELOG — Sito Dott.ssa Silvia Zagami

## v13.6.2 — Versione approvata

### Fixed
- Corretto il layout della Home su smartphone in orizzontale, eliminando lo spazio vuoto eccessivo prima delle credenziali professionali.
- Uniformata la spaziatura interna della scheda «Università di Torino / Specializzazione» nella pagina **Chi sono**, risolvendo anche il conflitto CSS che aggiungeva 25 px sopra il contenuto.
- Corretto il refuso «Dott.sa» nel titolo HTML della Home.

### Changed
- Aggiornati gli URL canonici, Open Graph e social delle sei pagine al dominio ufficiale `https://silviazagami.it/`.
- Rivisto il testo sulla medicina della riproduzione e PMA nella pagina **Chi sono**.
- Aggiornato «Scopri l’area riproduzione e PMA» per aprire direttamente la categoria **04** delle Prestazioni, già espansa.

### Added
- `robots.txt` e `sitemap.xml` con gli URL del sito ufficiale.

### Validation
- Approvata dall'utente la candidata `v13.6.2-rc.3`.
- File HTML/CSS/JavaScript e risorse del sito invariati rispetto alla RC3 approvata; modificati soltanto README e CHANGELOG per formalizzare la release.
- Verifiche sul nuovo dominio, sui collegamenti e sulle anteprime social da completare dopo la pubblicazione.

## v13.6.2-rc.3 — Candidata in revisione (NON PUBBLICATA)

### Fixed
- Corretta la spaziatura interna del riquadro formativo «Università di Torino / Specializzazione» nella pagina **Chi sono**: eliminati altezza minima e centraggio verticale forzato; applicato spazio uniforme sopra e sotto i due blocchi, con separatore centrale.
- Rimossa anche la spaziatura aggiuntiva di **25 px** imposta dal selettore preesistente `#chi-sono .timeline-inline`: era la causa residua dell'asimmetria.
- Aggiustamento mirato al CSS di `chi-sono.html`, senza modificare contenuti, colori, font, link o layout delle altre pagine.

### Invariato rispetto a rc.2
- Correzione Home orizzontale, SEO e dominio ufficiale, sitemap/robots, testo PMA e collegamento alla categoria 04 aperta automaticamente.
- La v13.6.1 rimane la versione stabile pubblicata fino all'approvazione.

### Validation
- Controlli automatici e confronto dei file inclusi nel pacchetto: vedere la guida privata esterna all'archivio.
- Collaudo visivo finale su dispositivi reali ancora richiesto.

## v13.6.2-rc.2 — Candidata in revisione (NON PUBBLICATA)

### Fixed
- Riequilibrate le due voci del riquadro formativo nella pagina **Chi sono**, senza cambiare lo stile visuale approvato.

### Changed
- Rivisto il testo della sezione «La medicina della riproduzione e PMA» nella pagina **Chi sono**, mantenendo il riferimento agli aspetti ostetrici e neonatali e all'appartenenza SIFES-MR.
- Rinominato il link in «Scopri l’area riproduzione e PMA».
- Aggiornato il collegamento per aprire direttamente il dettaglio **04 — Medicina della riproduzione e PMA**, già espanso, con il titolo visibile sotto l'intestazione fissa.

### Validation
- Nessuna modifica al sito pubblicato: la candidata necessita ancora dell'approvazione dopo il collaudo.
- Altri interventi SEO e correzioni responsive di v13.6.2-rc.1 conservati invariati.

## v13.6.2-rc.1 — Candidata precedente, non pubblicata

### Fixed
- Corretto il layout della Home su smartphone in orizzontale: altezza dell'immagine adattata e ridotti gli spazi vuoti prima delle credenziali professionali.
- Nascosta la dicitura decorativa «Scienza, cura, relazione» esclusivamente nel breakpoint landscape degli smartphone.

### Changed
- Sostituiti in tutte e sei le pagine i 30 riferimenti assoluti al precedente URL GitHub Pages nei metadati canonici e social, usando `https://silviazagami.it/`.
- Corretto il refuso nel titolo HTML della Home: «Dott.ssa» al posto di «Dott.sa».
- Aggiornato README con dominio ufficiale e documentazione pubblica essenziale.

### Added
- `sitemap.xml` con le sei pagine canoniche.
- `robots.txt` con regole di scansione e riferimento alla sitemap.

### Unchanged
- Testi e contenuti clinici, navigazione multipagina, logo, immagini e copertine social, icone di sistema, manifest, record DNS, impostazioni HTTPS.

### Validation
- La pubblicazione avverrà solo dopo il collaudo e l'approvazione della candidata.
- Il collaudo manuale su dispositivi Apple reali e la verifica delle anteprime social dopo la pubblicazione restano da completare.

## v13.6.1 — Approvata per il rilascio

### Changed
- Nome del collegamento Home Screen: «Dott.ssa Zagami» (meta Apple e manifest).
- Icona Home Screen: monogramma originale leggermente ridotto, sfondo uniforme, nessun bordo interno.
- Favicon coordinati; icone Android normali, maskable e monocromatiche per sistemi compatibili.
- Parametri cache busting delle icone aggiornati a `v13.6.1`.

### Unchanged
- Tutti i contenuti clinici e il layout delle sei pagine.
- Titoli di pagina e descrizioni SEO.
- Immagini Open Graph e anteprime WhatsApp.

### Validation
- Verifica statica di file HTML, manifest e dimensioni delle icone completata.
- Collaudo reale del collegamento Home Screen da eseguire dopo il deployment.

### Development history
- Candidate: `v13.6.1-rc.1` e `v13.6.1-rc.2`; `rc.2` approvata.

## v13.6.0 — Copertine social e icone multipiattaforma
- Aggiunti tag Open Graph, Twitter/X Card, titoli e descrizioni specifici per le sei pagine.
- Create quattro copertine social (Home, Chi sono, Prestazioni, Contatti) con foto originale e monogramma.
- Aggiunti favicon, icona Apple touch, icone Android e `site.webmanifest`.
- Nessuna modifica ai testi clinici e al layout.
- Commit di riferimento su `main`: `cab0cdcab104de238fbec07982f09c2d6244e871`.

## v13.5.1 — Prima release ufficiale tracciata
- Riorganizzata la pagina Prestazioni; rimosse ripetizioni e CTA duplicata.
- Corretto il margine del riquadro PMA su iPad verticale.
- Tag Git: `v13.5.1`; commit `07becea`.
