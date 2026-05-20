# telinit

> Cambia il runlevel SysV.
> Poiché il concetto di runlevel SysV è obsoleto, le richieste di runlevel verranno tradotte trasparentemente in richieste di attivazione di unità systemd.
> Maggiori informazioni: <https://manned.org/telinit>.

- Spegni la macchina:

`telinit 0`

- Riavvia la macchina:

`telinit 6`

- Cambia il runlevel SysV:

`telinit {{2|3|4|5}}`

- Passa alla modalità di ripristino:

`telinit 1`

- Ricarica la configurazione del demone:

`telinit q`

- Non inviare un messaggio wall prima del riavvio/spegnimento (6/0):

`telinit --no-wall {{valore}}`
