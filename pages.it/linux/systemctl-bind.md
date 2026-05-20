# systemctl bind

> Monta tramite bind in modo effimero un file o directory dall'host nel namespace di mount di un'unità.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#bind%20UNIT%20PATH%20%5BPATH%5D>.

- Monta tramite bind un percorso host nella stessa posizione all'interno dell'unità:

`systemctl bind {{unità}} /{{percorso/della/directory_host}}`

- Monta tramite bind un percorso host in una posizione diversa all'interno dell'unità:

`systemctl bind {{unità}} /{{percorso/della/directory_host}} /{{percorso/della/directory_unità}}`

- Monta tramite bind un percorso in sola lettura all'interno dell'unità:

`systemctl bind {{unità}} /{{percorso/della/directory_host}} --read-only`

- Crea il percorso di destinazione all'interno dell'unità prima del montaggio:

`systemctl bind {{unità}} /{{percorso/della/directory_host}} /{{percorso/della/directory_unità}} --mkdir`
