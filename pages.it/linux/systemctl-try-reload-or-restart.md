# systemctl try-reload-or-restart

> Ricarica una o più unità se lo supportano; altrimenti le riavvia.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#try-reload-or-restart%20PATTERN%E2%80%A6>.

- Ricarica o riavvia un'unità specifica:

`systemctl try-reload-or-restart {{unità}}`

- Ricarica o riavvia più unità:

`systemctl try-reload-or-restart {{unità1 unità2 ...}}`

- Ricarica o riavvia tutte le unità corrispondenti a un pattern:

`systemctl try-reload-or-restart '{{pattern}}'`
