# xauth

> Modifica e visualizza le informazioni di autorizzazione utilizzate per connettersi al server X.
> Maggiori informazioni: <https://manned.org/xauth>.

- Avvia la modalità interattiva con un file di autorità specifico (il valore predefinito è `~/.Xauthority`):

`xauth -f {{path/to/file}}`

- Mostra informazioni sul file di autorità:

`xauth info`

- Mostra le voci di autorizzazione per tutti i display:

`xauth list`

- Aggiungi un'autorizzazione per un display specifico:

`xauth add {{nome_display}} {{nome_protocollo}} {{chiave}}`

- Rimuovi l'autorizzazione per un display specifico:

`xauth remove {{nome_display}}`

- Stampa la voce di autorizzazione per il display corrente su `stdout`:

`xauth extract - $DISPLAY`

- Unisci le voci di autorizzazione da un file specifico nel database delle autorizzazioni:

`cat {{path/to/file}} | xauth merge -`

- Mostra aiuto:

`xauth --help`
