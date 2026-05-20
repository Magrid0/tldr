# systemctl reload-or-restart

> Ricarica le unità `systemd` o le riavvia.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#reload-or-restart%20PATTERN%E2%80%A6>.

- Ricarica o riavvia un'unità:

`systemctl reload-or-restart {{unità}}`

- Ricarica o riavvia più unità che corrispondono a un pattern:

`systemctl reload-or-restart {{pattern}}`

- Esegue il comando senza attendere il completamento dell'operazione:

`systemctl reload-or-restart {{unità}} --no-block`

- Applica il comando solo alle unità utente:

`systemctl reload-or-restart {{unità}} --user`
