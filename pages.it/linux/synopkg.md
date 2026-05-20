# synopkg

> Utilità di gestione pacchetti per Synology DiskStation Manager.
> Maggiori informazioni: <https://www.synology.com/dsm>.

- Elenca i nomi dei pacchetti installati:

`synopkg list --name`

- Elenca i pacchetti che dipendono da un pacchetto specifico:

`synopkg list --depend-on {{pacchetto}}`

- Avvia/Ferma un pacchetto:

`sudo synopkg {{start|stop}} {{pacchetto}}`

- Stampa lo stato di un pacchetto:

`synopkg status {{pacchetto}}`

- Disinstalla un pacchetto:

`sudo synopkg uninstall {{pacchetto}}`

- Controlla se sono disponibili aggiornamenti per un pacchetto:

`synopkg checkupdate {{pacchetto}}`

- Aggiorna tutti i pacchetti all'ultima versione:

`sudo synopkg upgradeall`

- Installa un pacchetto da un file synopkg:

`sudo synopkg install {{percorso/del/pacchetto.spk}}`
