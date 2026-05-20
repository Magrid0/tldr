# systemctl service-log-level

> Ottiene o imposta il livello di log runtime di un servizio tramite D-Bus.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#service-log-level%20SERVICE%20%5BLEVEL%5D>.

- Mostra il livello di log corrente di un servizio:

`systemctl service-log-level {{nome_servizio}}`

- Imposta il livello di log di un servizio (il nome del livello può essere sostituito con un numero da 0 a 7):

`systemctl service-log-level {{nome_servizio}} {{emerg|alert|crit|err|warning|notice|info|debug}}`
