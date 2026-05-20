# systemctl list-automounts

> Elenca le unità di automount attualmente in memoria, mostrando i percorsi di mount e i nomi delle unità.
> Vedi anche: `systemctl list-units`, `systemctl list-unit-files`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#list-automounts%20PATTERN%E2%80%A6>.

- Elenca le unità di automount attualmente in memoria:

`systemctl list-automounts`

- Elenca tutte le unità di automount, incluse quelle inattive:

`systemctl list-automounts {{[-a|--all]}}`

- Filtra le unità di automount per stato:

`systemctl list-automounts --state {{active|inactive|failed|...}}`

- Filtra le unità di automount per pattern di nome:

`systemctl list-automounts {{pattern1 pattern2 ...}}`
