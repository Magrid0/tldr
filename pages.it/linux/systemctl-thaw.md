# systemctl thaw

> Scongela (riattiva) una o più unità congelate.
> Le unità possono essere congelate con `systemctl freeze`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#thaw%20PATTERN%E2%80%A6>.

- Scongela un'unità specifica:

`systemctl thaw {{unità}}`

- Scongela più unità:

`systemctl thaw {{unità1 unità2 ...}}`

- Scongela tutte le unità attualmente congelate:

`systemctl thaw '*'`
