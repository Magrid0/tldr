# systemctl add-requires

> Aggiunge dipendenze `Requires` a un target per una o più unità.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#add-wants%20TARGET%20UNIT%E2%80%A6>.

- Aggiunge una dipendenza `Requires` da un target a un'unità:

`systemctl add-requires {{target}} {{unità}}`

- Aggiunge più dipendenze `Requires` contemporaneamente:

`systemctl add-requires {{target}} {{unità1 unità2 ...}}`

- Aggiunge una dipendenza `Requires` a livello utente:

`systemctl add-requires {{target}} {{unità}} --user`
