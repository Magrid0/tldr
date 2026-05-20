# systemctl cat

> Mostra il contenuto completo dei file di unità come li vede systemd.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#cat%20PATTERN%E2%80%A6>.

- Mostra il contenuto e il percorso assoluto di un file di unità:

`systemctl cat {{unità}}`

- Mostra il contenuto di più file di unità:

`systemctl cat {{unità1 unità2 ...}}`

- Mostra il contenuto di un file di unità per un template:

`systemctl cat {{template@}}`

- Mostra il contenuto di un file di unità utente:

`systemctl cat {{unità}} --user`
