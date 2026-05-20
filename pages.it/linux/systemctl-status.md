# systemctl status

> Mostra lo stato delle unità systemd.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#status%20PATTERN%E2%80%A6%7CPID%E2%80%A6%5D>.

- Mostra lo stato di un'unità systemd:

`systemctl status {{unità}}.{{service|timer|socket|target|...}}`

- Mostra lo stato delle unità fallite:

`systemctl status --failed`

- Elenca tutti i servizi in esecuzione:

`systemctl status`

- Elenca tutte le unità nel sistema:

`systemctl status {{[-a|--all]}}`

- Elenca tutte le unità di un tipo specifico:

`systemctl status {{[-t|--type]}} {{service|timer|socket|target|...}}`

- Elenca tutte le unità con uno stato specifico:

`systemctl status --state {{active|inactive|failed}}`

- Mostra lo stato di un'unità utente:

`systemctl status {{unità}} --user`
