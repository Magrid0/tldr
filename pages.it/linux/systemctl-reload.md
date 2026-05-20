# systemctl reload

> Ricarica la configurazione di un servizio senza riavviarlo.
> Questo ricarica il servizio stesso (come le configurazioni di Apache o `nginx`), non il file di unità systemd.
> Per ricaricare i file di unità, usa `systemctl daemon-reload`.

- Ricarica un servizio:

`systemctl reload {{nginx}}`

- Ricarica più servizi:

`systemctl reload {{unità1 unità2 ...}}`

- Ricarica un servizio per l'utente corrente:

`systemctl reload {{pipewire}} --user`
