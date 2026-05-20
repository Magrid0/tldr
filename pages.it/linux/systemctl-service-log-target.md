# systemctl service-log-target

> Ottiene o imposta la destinazione di log per un servizio.
> Funziona solo per servizi integrati con D-Bus.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#service-log-target%20SERVICE%20%5BTARGET%5D>.

- Mostra la destinazione di log corrente per un servizio:

`systemctl service-log-target {{nome_servizio}}`

- Imposta la destinazione di log su `console` (invia i log a `stderr`):

`systemctl service-log-target {{nome_servizio}} console`

- Imposta la destinazione di log su `journal` (invia i log a `systemd-journald`):

`systemctl service-log-target {{nome_servizio}} journal`

- Imposta la destinazione di log su `syslog` (invia i log a `/dev/log`):

`systemctl service-log-target {{nome_servizio}} syslog`

- Permette a systemd di scegliere una destinazione di log appropriata:

`systemctl service-log-target {{nome_servizio}} auto`

- Disabilita tutto l'output di log:

`systemctl service-log-target {{nome_servizio}} null`
