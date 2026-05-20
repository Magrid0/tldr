# systemctl is-enabled

> Controlla se i file di unità sono abilitati.
> Vedi anche: `systemctl enable`, `systemctl disable`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#is-enabled%20UNIT%E2%80%A6>.

- Mostra lo stato di abilitazione:

`systemctl is-enabled {{unità1 unità2 ...}}`

- Sopprime l'output e restituisce solo il codice di uscita:

`systemctl is-enabled {{unità}} {{[-q|--quiet]}}`

- Mostra i target di installazione e i percorsi dei symlink:

`systemctl is-enabled {{unità}} {{[-l|--full]}}`
