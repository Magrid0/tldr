# systemctl is-active

> Controlla se una o più unità systemd sono attive.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#is-active%20PATTERN%E2%80%A6>.

- Controlla se un'unità è attiva:

`systemctl is-active {{unità}}`

- Controlla se più unità sono attive:

`systemctl is-active {{unità1 unità2 ...}}`

- Controlla se un'unità è attiva senza stampare lo stato su `stdout`:

`systemctl is-active {{unità}} {{[-q|--quiet]}}`

- Controlla se un'unità utente è attiva:

`systemctl is-active {{unità}} --user`
