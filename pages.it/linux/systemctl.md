# systemctl

> Controlla il sistema systemd e il gestore dei servizi.
> Alcuni sottocomandi come `disable`, `status`, `reboot` ecc. hanno la propria documentazione d'uso.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html>.

- Mostra tutti i servizi in esecuzione:

`systemctl status`

- Elenca le unità fallite:

`systemctl --failed`

- Avvia/Ferma/Riavvia/Ricarica/Mostra lo stato di un servizio:

`systemctl {{start|stop|restart|reload|status}} {{unità}}`

- Abilita/Disabilita un'unità per l'avvio all'accensione:

`systemctl {{enable|disable}} {{unità}}`

- Ricarica systemd, cerca unità nuove o modificate:

`systemctl daemon-reload`

- Controlla se un'unità è attiva/abilitata/fallita:

`systemctl {{is-active|is-enabled|is-failed}} {{unità}}`

- Elenca tutte le unità di servizio/socket/automount filtrando per stato running/failed:

`systemctl list-units {{[-t|--type]}} {{service|socket|automount|...}} --state {{failed|running}}`

- Mostra il contenuto e il percorso assoluto di un file di unità o lo modifica:

`systemctl {{cat|edit}} {{unità}}`
