# systemctl show

> Mostra le proprietà delle unità o di systemd stesso.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#show%20PATTERN%E2%80%A6%7CJOB%E2%80%A6>.

- Mostra le proprietà del gestore dei servizi di sistema:

`systemctl show`

- Mostra le proprietà del gestore dei servizi utente:

`systemctl show --user`

- Mostra le proprietà di un'unità specifica:

`systemctl show {{unità}}`

- Mostra le proprietà di un'unità utente specifica:

`systemctl show {{unità}} --user`

- Include le proprietà vuote nell'elenco:

`systemctl show {{[-a|--all]}}`

- Mostra solo le proprietà specificate:

`systemctl show {{unità}} {{[-p|--property]}} {{Wants,Conflicts,...}}`
