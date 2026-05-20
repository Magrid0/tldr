# synoupgrade

> Aggiorna Synology DiskStation Manager (DSM) - il sistema operativo Synology NAS.
> Maggiori informazioni: <https://www.synology.com/dsm>.

- Controlla se sono disponibili aggiornamenti:

`sudo synoupgrade --check`

- Controlla la presenza di patch senza aggiornare la versione DSM:

`sudo synoupgrade --check-smallupdate`

- Scarica l'ultimo aggiornamento disponibile (usa `--download-smallupdate` per le patch):

`sudo synoupgrade --download`

- Avvia il processo di aggiornamento:

`sudo synoupgrade --start`

- Aggiorna automaticamente all'ultima versione:

`sudo synoupgrade --auto`

- Applica automaticamente le patch senza aggiornare la versione DSM:

`sudo synoupgrade --auto-smallupdate`

- Aggiorna il DSM usando un file di patch (deve essere un percorso assoluto):

`sudo synoupgrade --patch /{{percorso/del/file.pat}}`

- Mostra aiuto:

`synoupgrade`
