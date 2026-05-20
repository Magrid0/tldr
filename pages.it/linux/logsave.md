# logsave

> Salva l'output di un comando in un file di log.
> Maggiori informazioni: <https://manned.org/logsave>.

- Esegue un comando con gli argomenti specificati e salva il suo output in un file di log:

`logsave {{path/to/logfile}} {{command}}`

- Prende l'input da `stdin` e lo salva in un file di log:

`logsave {{logfile}} -`

- Aggiunge l'output a un file di log, invece di sostituirne il contenuto corrente:

`logsave -a {{logfile}} {{command}}`

- Mostra output verboso:

`logsave -v {{logfile}} {{command}}`
