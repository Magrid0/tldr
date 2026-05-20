# systemctl unmask

> Scopre le unità per renderle nuovamente avviabili.
> Annulla l'effetto di `systemctl mask`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#unmask%20UNIT%E2%80%A6>.

- Scopre un servizio:

`systemctl unmask {{nome_servizio}}`

- Scopre e avvia un servizio immediatamente:

`systemctl unmask {{nome_servizio}} --now`

- Scopre un servizio utente:

`systemctl unmask {{nome_servizio}} --user`
