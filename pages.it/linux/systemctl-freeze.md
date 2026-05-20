# systemctl freeze

> Congela una o più unità.
> Le unità congelate possono essere riprese con `systemctl thaw`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#freeze%20PATTERN%E2%80%A6>.

- Congela un'unità specifica:

`systemctl freeze {{unità}}`

- Congela più unità:

`systemctl freeze {{unità1 unità2 ...}}`

- Congela tutte le unità in esecuzione:

`systemctl freeze '*'`
