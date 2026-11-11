# Sito web — Dott.ssa Silvia Zagami

Sito informativo professionale della Dott.ssa Silvia Zagami, specialista in Ostetricia e Ginecologia. Il progetto è **multipagina**, responsive e pubblicato tramite GitHub Pages.

## Stato del progetto

- **Versione dei file preparati:** v13.4 (aggiornamento navigazione)
- **Versione attualmente online:** verificare sempre sul sito pubblico dopo il caricamento
- **Repository:** `willi1am/Silvia-preview`
- **Ramo di pubblicazione:** `main`
- **Hosting:** GitHub Pages (`main` → `/(root)`)
- **Tecnologie:** HTML, CSS e JavaScript, senza framework o servizi di hosting aggiuntivi
- **Dominio personalizzato:** da configurare separatamente, quando acquistato

## Struttura del sito

| File | Pagina |
| --- | --- |
| `index.html` | Home |
| `chi-sono.html` | Profilo, formazione, esperienza ospedaliera |
| `prestazioni.html` | Aree cliniche e prestazioni dettagliate |
| `contatti.html` | Banchette, Ciriè, Torino e recapiti |
| `privacy.html` | Informativa privacy |
| `cookie.html` | Informazioni sui cookie |

Le sei pagine contengono attualmente gli stili e le risorse necessarie nei rispettivi HTML. I collegamenti interni sono relativi per funzionare sia su GitHub Pages sia con un dominio personalizzato.

## Aggiornare il sito da iPhone o iPad

1. Salvare localmente lo ZIP completo della nuova versione, verificando che si apra.
2. Prima di sostituire `main`, conservare un riferimento recuperabile della versione pubblicata tramite branch di backup o tag.
3. Estrarre il pacchetto di pubblicazione. **Non caricare direttamente lo ZIP.**
4. In GitHub → `Silvia-preview` → ramo **`main`**, usare `Upload files` e caricare i **sei file HTML** nella **radice** del repository.
5. Se i file non possono essere caricati contemporaneamente, caricare prima le cinque pagine secondarie e **`index.html` per ultimo**.
6. Salvare con un commit descrittivo, ad esempio `Pubblicazione sito Silvia v13.4`.
7. Aprire il sito online e controllare Home, Chi sono, Prestazioni, Contatti, Privacy e Cookie, sia da smartphone sia da desktop.

**Attenzione:** non selezionare il ramo di backup per la pubblicazione. La modifica al README da sola non aggiorna il sito online.

## Backup e versionamento

- Conservare uno ZIP completo per ciascuna release importante, scaricabile e apribile in locale.
- Per versioni stabili, utilizzare un ramo o un tag nominato, ad esempio `backup-v12.2`, `v13.3`, `v13.4`.
- GitHub conserva anche la cronologia dei commit; i backup devono permettere il ripristino senza ambiguità.
- Non pubblicare screenshot privati, credenziali, documenti riservati o dati di pazienti nel repository pubblico.

## Privacy e contenuti

- Il sito è informativo e non include un modulo per inviare dati clinici.
- I collegamenti esterni, i trattamenti e le informative vanno rivalutati quando si attivano nuove funzioni, come prenotazioni e analytics.
- La sede di Torino è indicata senza indirizzo pubblico, su richiesta.
- La disponibilità di alcune prestazioni può variare in base alla sede: non promettere servizi non confermati.
- Ogni informazione clinica e professionale deve essere approvata da Silvia prima della pubblicazione.

## Registro sintetico delle versioni

- **v12.2:** versione precedente a pagina unica, da conservare come backup.
- **v13.0:** passaggio alla struttura multipagina.
- **v13.2:** revisione della homepage e dei collegamenti.
- **v13.3:** semplificazione di Chi sono, Prestazioni e Contatti; titolo «Parliamone» senza punto.
- **v13.4:** spaziatura interna migliorata per il menu mobile; sottolineatura rosa più visibile per la pagina attiva nel menu desktop/iPad.
