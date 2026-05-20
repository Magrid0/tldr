# logger

> Aggiunge messaggi al log di sistema.
> Maggiori informazioni: <https://manned.org/logger>.

- Registra un messaggio in syslog:

`logger {{message}}`

- Prende l'input da `stdin` e lo registra in syslog:

`echo {{log_entry}} | logger`

- Invia l'output a un server syslog remoto in esecuzione su una determinata porta. La porta predefinita è 514:

`echo {{log_entry}} | logger {{[-n|--server]}} {{hostname}} {{[-P|--port]}} {{port}}`

- Usa un tag specifico per ogni riga registrata. Il valore predefinito è il nome dell'utente connesso:

`echo {{log_entry}} | logger {{[-t|--tag]}} {{tag}}`

- Registra messaggi con una data priorità. Il valore predefinito è `user.notice`. Vedi `man logger` per tutte le opzioni di priorità:

`echo {{log_entry}} | logger {{[-p|--priority]}} {{user.warning}}`
