# abrt-cli

> Strumento di segnalazione automatica degli errori per sistemi basati su Fedora.
> Utilizzato per rilevare, analizzare e segnalare crash di applicazioni.
> Maggiori informazioni: <https://abrt.readthedocs.io/en/latest/usage.html>.

- Elenca i problemi rilevati:

`abrt-cli list`

- Mostra i dettagli di un problema specifico:

`abrt-cli info {{id_problema}}`

- Rimuove un rapporto di crash:

`abrt-cli remove {{id_problema}}`

- Segnala un problema al tracker di bug configurato (es. Bugzilla):

`abrt-cli report {{id_problema}}`

- Monitora un file di log e avvia un programma quando viene trovata una corrispondenza:

`abrt-watch-log -F {{stringa_errore}} {{/var/log/myapp.log}} {{notify-send "Crash detected"}}`

- Genera un rapporto per il debug manuale:

`abrt-cli report {{[-a|--analyze]}} {{id_problema}}`
