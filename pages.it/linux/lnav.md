# lnav

> Visualizzatore avanzato di file di log per analizzare log con poca o nessuna configurazione.
> Maggiori informazioni: <https://docs.lnav.org/en/latest/cli.html>.

- Visualizza i log di un programma, specificando file di log, directory o URL:

`lnav {{path/to/log_or_directory|url}}`

- Visualizza i log di un host remoto specifico (richiede l'accesso SSH senza password):

`lnav {{ssh}} {{user}}@{{host1.example.com}}:{{/var/log/syslog.log}}`

- Convalida il formato dei file di log rispetto alla configurazione e segnala eventuali errori:

`lnav -C {{path/to/log_directory}}`
