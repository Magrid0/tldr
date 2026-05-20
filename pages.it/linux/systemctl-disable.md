# systemctl disable

> Disabilita i servizi systemd.
> Vedi anche: `systemctl revert`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#disable%20UNIT%E2%80%A6>.

- Impedisce a un servizio di essere eseguito all'avvio:

`systemctl disable {{unità}}`

- Impedisce a un servizio di essere eseguito all'avvio e ne ferma l'esecuzione corrente:

`systemctl disable {{unità}} --now`

- Impedisce a un servizio utente di essere eseguito al login:

`systemctl disable {{unità}} --user`
