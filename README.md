# Dott.ssa Silvia Zagami — Sito professionale

Sito informativo della Dott.ssa Silvia Zagami, specialista in Ostetricia e Ginecologia.

**Sito web ufficiale:** https://silviazagami.it/  
**Versione del pacchetto:** v13.6.3 (approvata, pronta per la pubblicazione)  
**Versione precedente pubblicata:** v13.6.2  
**Pubblicazione:** GitHub Pages, dominio personalizzato e HTTPS

## Pagine

- `index.html` — Home
- `chi-sono.html` — Profilo professionale
- `prestazioni.html` — Prestazioni
- `contatti.html` — Contatti e sedi
- `privacy.html` — Informativa sulla privacy
- `cookie.html` — Informazioni sui cookie

## Struttura tecnica

Il sito è statico e responsive (HTML, CSS e JavaScript). Per la visualizzazione non richiede database o servizi applicativi esterni.

- `assets/` — favicon, icone multipiattaforma e copertine social.
- `site.webmanifest` — metadati del collegamento alla schermata Home e icone per i dispositivi compatibili.
- `robots.txt` — regole di scansione e posizione della sitemap.
- `sitemap.xml` — URL pubblici delle sei pagine.
- `CNAME` — dominio personalizzato configurato su GitHub Pages.
- `CHANGELOG.md` — cronologia delle modifiche.

## SEO e anteprime di condivisione

- URL canonici e metadati Open Graph/Twitter fanno riferimento al dominio ufficiale `silviazagami.it`.
- Le immagini social approvate restano in `assets/` senza modifiche.
- Sitemap e robots.txt facilitano la scoperta delle pagine da parte dei motori di ricerca, ma non garantiscono l'indicizzazione né il posizionamento.
- La gestione dell'indicizzazione può essere monitorata tramite Google Search Console.

Il collegamento dalla sezione PMA della pagina **Chi sono** apre direttamente la categoria 04 della pagina Prestazioni.

## Note sui contenuti

Le informazioni cliniche e le prestazioni disponibili devono essere confermate direttamente con la professionista; la disponibilità può variare tra le sedi.

## Versioni

Le versioni ufficiali sono consultabili nella sezione [Releases](https://github.com/willi1am/Silvia-preview/releases). Ogni tag identifica il codice di una release.

## Diritti

Contenuti e materiali del sito appartengono ai rispettivi titolari. La disponibilità pubblica del codice sorgente non implica autorizzazione al riutilizzo delle fotografie, del logo o dei testi.

## Aggiornamento v13.6.3

Corretto il collegamento Facebook nella pagina `contatti.html`: ora punta direttamente a `https://www.facebook.com/61595187193989/`, senza URL `/share/` né parametri aggiuntivi. Nessun cambiamento all'interfaccia, agli altri contenuti o alle altre risorse del sito. La candidata `v13.6.3-rc.2` è stata approvata dall'utente e la modifica deve essere verificata anche dopo il deploy sul dominio ufficiale.
