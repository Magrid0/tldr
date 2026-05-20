# systemctl help

> Mostra le pagine di manuale per una o più unità, o per l'unità a cui appartiene un processo (tramite PID).
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#help%20PATTERN%E2%80%A6%7CPID%E2%80%A6>.

- Mostra la pagina di manuale per un'unità specifica:

`systemctl help {{unità}}`

- Mostra le pagine di manuale per più unità:

`systemctl help {{unità1 unità2 ...}}`

- Mostra la pagina di manuale per un'unità utente:

`systemctl help {{unità}} --user`

- Mostra la pagina di manuale senza un paginatore (tutta in una volta):

`systemctl help {{unità}} --no-pager`

- Mostra la pagina di manuale per l'unità di un processo tramite PID:

`systemctl help {{pid}}`
