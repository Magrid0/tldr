# systemctl list-units

> Elenca le unità che systemd ha attualmente in memoria.
> Vedi anche: `systemctl list-unit-files`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#list-units%20PATTERN%E2%80%A6>.

- Elenca le unità che sono attive, hanno job in sospeso o sono fallite:

`systemctl list-units`

- Elenca tutte le unità, incluse quelle inattive:

`systemctl list-units {{[-a|--all]}}`

- Filtra per tipo di unità:

`systemctl list-units {{[-t|--type]}} {{service|socket|timer|...}}`

- Filtra per stato:

`systemctl list-units --state {{running|listening|dead|...}}`

- Filtra per pattern di nome:

`systemctl list-units 'systemd*'`

- Stampa l'output direttamente su `stdout`:

`systemctl list-units --no-pager`

- Stampa l'output senza intestazioni o piè di pagina (per script):

`systemctl list-units --no-legend`
