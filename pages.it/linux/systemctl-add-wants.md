# systemctl add-wants

> Aggiunge dipendenze `Wants` a un target per una o più unità.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#add-wants%20TARGET%20UNIT%E2%80%A6>.

- Aggiunge una dipendenza `Wants` da un target a un'unità:

`systemctl add-wants {{target}} {{unità}}`

- Aggiunge più dipendenze `Wants` contemporaneamente:

`systemctl add-wants {{target}} {{unità1 unità2 ...}}`

- Aggiunge una dipendenza `Wants` a livello utente:

`systemctl add-wants {{target}} {{unità}} --user`
