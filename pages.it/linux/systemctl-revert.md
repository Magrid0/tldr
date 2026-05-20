# systemctl revert

> Ripristina i file di unità alle loro versioni originali del fornitore.
> Annulla gli effetti di `edit`, `enable`, `disable`, `set-property` e `mask`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#revert%20UNIT%E2%80%A6>.

- Ripristina i file di unità alle loro impostazioni predefinite:

`systemctl revert {{unità1 unità2 ...}}`

- Ripristina un file di unità utente:

`systemctl revert {{unità}} --user`
