# logwatch

> Riassume molti log diversi per servizi comuni (es. apache, pam_unix, sshd, ecc.) in un unico report.
> Maggiori informazioni: <https://manned.org/logwatch>.

- Analizza i log per un intervallo di date a un certo livello di dettaglio:

`logwatch --range {{yesterday|today|all|help}} --detail {{low|medium|others}}'`

- Limita il report a includere solo informazioni per un servizio selezionato:

`logwatch --range {{all}} --service {{apache|pam_unix|...}}`
