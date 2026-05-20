# systemctl restart

> Ferma e poi avvia una o più unità systemd.
> Può essere usato al posto di `systemctl start` su un'unità ferma, ma `start` è più sicuro per evitare di riavviare accidentalmente un'unità in esecuzione.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#restart%20PATTERN%E2%80%A6>.

- Riavvia un'unità:

`systemctl restart {{unità}}`

- Riavvia più di un'unità:

`systemctl restart {{unità1 unità2 ...}}`

- Riavvia un'unità utente:

`systemctl restart {{unità}} --user`
