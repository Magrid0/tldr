# systemctl is-failed

> Controlla se una o più unità systemd sono fallite.
> Vedi anche: `systemctl is-active`, `systemctl status`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#is-failed%20PATTERN%E2%80%A6>.

- Controlla se ci sono unità fallite:

`systemctl is-failed`

- Controlla se un'unità o più unità sono fallite:

`systemctl is-failed {{unità1 unità2 ...}}`

- Sopprime l'output e restituisce solo il codice di uscita:

`systemctl is-failed {{unità}} {{[-q|--quiet]}}`

- Controlla se un'unità utente è fallita:

`systemctl is-failed {{unità}} --user`
