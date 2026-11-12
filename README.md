# Sito web — Dott.ssa Silvia Zagami

Sito informativo professionale **multipagina**, responsive, pubblicato con GitHub Pages.

## Versione del progetto

- **Versione approvata del codice:** `v13.5.1`
- **Repository:** `willi1am/Silvia-preview`
- **Ramo di pubblicazione:** `main` (GitHub Pages, cartella `/(root)`)
- **Stato della pubblicazione:** da verificare su GitHub Pages dopo ogni aggiornamento
- **Sede Torino:** indicazioni su richiesta, senza indirizzo pubblico
- **Dominio personalizzato e email sul dominio:** da configurare separatamente

Il numero di versione identifica il pacchetto di codice approvato. Per attestare quale versione è **effettivamente online**, fare riferimento al commit verificato e al relativo tag Git (non al solo README).

## Pagine

| File | Pagina |
| --- | --- |
| `index.html` | Home |
| `chi-sono.html` | Profilo, formazione e attività ospedaliera |
| `prestazioni.html` | Aree cliniche e prestazioni dettagliate |
| `contatti.html` | Sedi e contatti |
| `privacy.html` | Informativa privacy |
| `cookie.html` | Informazioni sui cookie |

Le pagine includono gli stili e le risorse necessarie; non sono richiesti hosting a pagamento, database, CMS o passaggi di compilazione.

## Modifiche in v13.5.1

- Pagina **Prestazioni**: testo iniziale semplificato, seguito dai quattro ambiti clinici.
- Sezione **«Come posso aiutarti»** spostata sotto le schede: ora introduce le cinque categorie espandibili.
- Eliminati i titoli e le frasi ripetitive, compreso il richiamo finale «Vuoi conoscere la disponibilità?».
- Mantenuto il riquadro «Hai bisogno di informazioni su una prestazione?».
- Corretto il margine inferiore di «Membro SIFES-MR» su iPad verticale.
- Nessuna modifica sostanziale alle altre pagine, ai recapiti e alle informative legali rispetto alla candidata approvata.

## Pubblicazione da iPhone/iPad

1. **Conserva il backup** in `Sito Silvia Zagami/02_RELEASE_APPROVATE/v13.5.1/` nell'app File.
2. Estrai l'archivio `Sito_Silvia_v13.5.1_GitHub.zip` (non caricare lo ZIP nel repository).
3. Apri il repository GitHub, seleziona `main` e usa **Upload files**.
4. Carica i sei file HTML e `README.md` + `CHANGELOG.md` **nella radice** del repository. Possono essere caricati in un unico commit.
5. Messaggio di commit suggerito: `fix: streamline services page and PMA card spacing (v13.5.1)`.
6. Apri il sito pubblico e controlla Home, Prestazioni, l'espansione delle cinque categorie, Contatti, Privacy e Cookie.
7. Solo **dopo la verifica online**, crea un tag Git `v13.5.1` sul commit pubblicato e, facoltativamente, una GitHub Release con le note di `CHANGELOG.md`.

Se ci sono problemi, interrompi il rilascio e ripristina il commit precedente da GitHub; non creare il tag su una versione che non hai verificato.

## Convenzione di versionamento

- `MAJOR.MINOR.PATCH` — convenzione ispirata a Semantic Versioning, adattata a questo sito.
- `-rc.1` — candidata da provare; non è una release ufficiale.
- Una versione ufficiale è **immutabile**: nuove correzioni ricevono un nuovo numero di versione.
- Ogni versione pubblicata si associa a un commit, un tag Git immutabile e un backup ZIP locale.
- Non occorre un ramo di backup per ogni release; i tag sono riferimenti puntuali più adatti.

## Sicurezza e privacy

Non inserire nel repository pubblico credenziali, dati di pazienti, referti o documenti riservati. Prima di integrare analytics, calendari o nuovi servizi online, verificare gli effetti sulla privacy e sulle informative. Il sito non sostituisce i canali sanitari di comunicazione protetti.
