# systemctl edit

> Modifica i file di unità systemd.
> Vedi anche: `systemctl revert`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#edit%20UNIT%E2%80%A6>.

- Sovrascrive un file di unità in modo non distruttivo:

`sudo systemctl edit {{file_unità}}`

- Modifica un file di unità:

`sudo systemctl edit {{file_unità}} {{[-l|--full]}}`

- Crea un nuovo file di unità:

`sudo systemctl edit {{file_unità}} {{[-lf|--full --force]}}`

- Sovrascrive un file di unità utente:

`systemctl edit {{file_unità}} --user`
