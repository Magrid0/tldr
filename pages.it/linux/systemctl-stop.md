# systemctl stop

> Ferma le unità systemd.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#stop%20PATTERN%E2%80%A6>.

- Ferma un'unità:

`systemctl stop {{unità}}`

- Ferma un servizio e sopprime gli avvisi:

`systemctl stop {{unità}} --no-warn`

- Ferma un'unità utente:

`systemctl stop {{unità}} --user`
