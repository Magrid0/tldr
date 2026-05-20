# sbcast

> Invia un file ai nodi allocati di un job.
> Questo comando dovrebbe essere usato solo all'interno di un job batch Slurm.
> Maggiori informazioni: <https://slurm.schedmd.com/sbcast.html>.

- Invia un file a tutti i nodi allocati al job corrente:

`sbcast {{percorso/del/file}} {{percorso/di/destinazione}}`

- Rileva automaticamente le librerie condivise da cui il file trasmesso dipende e le trasmette anch'esse:

`sbcast --send-libs={{yes}} {{percorso/dell/eseguibile}} {{percorso/di/destinazione}}`
