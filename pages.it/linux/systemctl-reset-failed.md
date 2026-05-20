# systemctl reset-failed

> Reimposta lo stato "fallito" di una o più unità.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#reset-failed%20%5BPATTERN%E2%80%A6%5D>.

- Reimposta lo stato fallito di tutte le unità:

`systemctl reset-failed`

- Reimposta lo stato fallito di un'unità specifica:

`systemctl reset-failed {{unità}}`

- Reimposta più unità contemporaneamente:

`systemctl reset-failed {{unità_1 unità_2 ...}}`
