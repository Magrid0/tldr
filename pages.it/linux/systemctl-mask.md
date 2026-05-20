# systemctl mask

> Collega le unità a `/dev/null` in modo che non possano essere avviate.
> Vedi anche: `systemctl revert`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#mask%20UNIT%E2%80%A6>.

- Maschera un servizio:

`systemctl mask {{nome_servizio}}`

- Assicura che il servizio sia fermo durante la mascheratura:

`systemctl mask {{nome_servizio}} --now`

- Maschera un servizio utente:

`systemctl mask {{nome_servizio}} --user`
