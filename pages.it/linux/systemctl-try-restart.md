# systemctl try-restart

> Riavvia una o più unità solo se sono attualmente in esecuzione.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#try-restart%20PATTERN%E2%80%A6>.

- Riavvia un'unità specifica se è in esecuzione:

`systemctl try-restart {{unità}}`

- Riavvia più unità se sono in esecuzione:

`systemctl try-restart {{unità1 unità2 ...}}`

- Riavvia tutte le unità corrispondenti a un pattern se sono in esecuzione:

`systemctl try-restart '{{pattern}}'`
