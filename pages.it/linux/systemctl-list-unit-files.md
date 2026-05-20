# systemctl list-unit-files

> Elenca i file di unità installati e i loro stati di abilitazione.
> Vedi anche: `systemctl list-units`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#list-unit-files%20PATTERN%E2%80%A6>.

- Elenca i file di unità installati e i loro stati:

`systemctl list-unit-files`

- Filtra per stato:

`systemctl list-unit-files --state {{enabled|disabled|static|...}}`

- Filtra per tipo di unità:

`systemctl list-unit-files {{[-t|--type]}} {{service|socket|timer|...}}`

- Filtra per pattern di nome:

`systemctl list-unit-files '{{sshd*}}'`

- Stampa l'output direttamente su `stdout`:

`systemctl list-unit-files --no-pager`

- Stampa l'output senza intestazioni o piè di pagina:

`systemctl list-unit-files --no-legend`
