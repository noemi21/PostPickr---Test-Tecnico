PostPickr - Test Tecnico
Piccola demo client-side che mostra una lista di utenti, il conteggio dei loro post, statistiche sulle email e il titolo più lungo. I dati provengono da JSONPlaceholder (users + posts). Nessuna dipendenza esterna: HTML/CSS/JS. Funzionalità
- Elenco utenti (nome, email, città, azienda)
- Conteggio post per utente (calcolato client-side)
- Statistiche email (.net / .com / altri)
- Titolo di post più lungo e relativo autore (solo tra gli utenti visibili)
- Eliminazione utente dalla vista (solo client, non persistente)
- Responsive e accessibile (uso di aria-live per aggiornamenti di stato)
File principali
- 'index.html'  — intera applicazione (HTML, CSS e JavaScript inline)
Requisiti
- Browser moderno con supporto Fetch API (Chrome / Edge / Firefox / Safari)
- Non sono necessari tool o build
Esecuzione locale
Per evitare problemi legati a restrizioni di origine (CORS), servire i file tramite un server HTTP locale. Live Server (estensione di VS Code) è sufficiente ed è il modo più semplice:
- Con Live Server (VS Code): click destro su 'index.html' -> "Open with Live Server" oppure usa il pulsante "Go Live" in basso a destra.
