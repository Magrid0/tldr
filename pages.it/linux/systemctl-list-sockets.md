# systemctl list-sockets

> Elenca le unità socket attive attualmente in memoria, ordinate per indirizzo di ascolto.
> Vedi anche: `systemctl list-units`, `systemctl list-unit-files`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#list-sockets%20PATTERN%E2%80%A6>.

- Elenca le unità socket attive attualmente in memoria:

`systemctl list-sockets`

- Elenca le unità socket attive con i loro tipi di socket:

`systemctl list-sockets --show-types`

- Elenca tutte le unità socket, incluse quelle inattive e fallite:

`systemctl list-sockets {{[-a|--all]}}`

- Elenca le unità socket filtrate per stato:

`systemctl list-sockets --state {{active|inactive|failed|...}}`

- Elenca le unità socket che corrispondono a un pattern di nome:

`systemctl list-sockets {{pattern1 pattern2 ...}}`
