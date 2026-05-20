# systemctl list-timers

> Elenca tutti i timer systemd attivi.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#list-timers%20PATTERN%E2%80%A6>.

- Elenca tutti i timer attivi:

`systemctl list-timers`

- Elenca tutti i timer, inclusi quelli inattivi:

`systemctl list-timers {{[-a|--all]}}`

- Elenca i timer che corrispondono a un pattern:

`systemctl list-timers {{pattern}}`

- Elenca i timer che corrispondono a uno stato specifico:

`systemctl list-timers --state {{active|inactive|failed|...}}`
