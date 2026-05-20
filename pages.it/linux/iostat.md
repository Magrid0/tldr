# iostat

> Riporta le statistiche per dispositivi e partizioni.
> Maggiori informazioni: <https://manned.org/iostat>.

- Mostra un report delle statistiche di CPU e disco dall'avvio del sistema:

`iostat`

- Mostra un report delle statistiche di CPU e disco con unità convertite in megabyte:

`iostat -m`

- Mostra le statistiche della CPU:

`iostat {{[-c|--compact]}}`

- Mostra le statistiche del disco con i nomi dei dischi (incluso LVM):

`iostat -N`

- Mostra le statistiche estese del disco con i nomi dei dischi per il dispositivo "sda":

`iostat -xN {{sda}}`

- Mostra report incrementali delle statistiche di CPU e disco ogni 2 secondi:

`iostat {{2}}`
