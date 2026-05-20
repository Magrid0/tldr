# systemctl enable

> Abilita i servizi systemd.
> Vedi anche: `systemctl revert`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#enable%20UNIT%E2%80%A6>.

- Abilita un servizio per l'esecuzione all'avvio:

`systemctl enable {{unità}}`

- Abilita un servizio per l'esecuzione all'avvio e lo avvia ora:

`systemctl enable {{unità}} --now`

- Abilita un'unità utente per l'esecuzione al login:

`systemctl enable {{unità}} --user`
