# swupd

> Utilità di gestione pacchetti per Clear Linux.
> Maggiori informazioni: <https://www.clearlinux.org/clear-linux-documentation/guides/clear/swupd.html>.

- Aggiorna all'ultima versione:

`sudo swupd update`

- Mostra la versione corrente e controlla se ne esiste una più recente:

`swupd check-update`

- Elenca i bundle installati:

`swupd bundle-list`

- Trova il bundle in cui esiste un pacchetto desiderato:

`swupd search -b {{pacchetto}}`

- Installa un nuovo bundle:

`sudo swupd bundle-add {{bundle}}`

- Rimuove un bundle:

`sudo swupd bundle-remove {{bundle}}`

- Corregge file danneggiati o mancanti:

`sudo swupd verify`
