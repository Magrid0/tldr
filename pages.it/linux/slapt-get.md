# slapt-get

> Un sistema simile ad `apt` per la gestione dei pacchetti Slackware.
> Le fonti dei pacchetti devono essere configurate nel file slapt-getrc.
> Maggiori informazioni: <https://software.jaos.org/git/slapt-get/plain/README>.

- Aggiorna la lista dei pacchetti e versioni disponibili:

`slapt-get --update`

- Installa un pacchetto, o lo aggiorna all'ultima versione disponibile:

`slapt-get --install {{pacchetto}}`

- Rimuove un pacchetto:

`slapt-get --remove {{pacchetto}}`

- Aggiorna tutti i pacchetti installati alle loro ultime versioni disponibili:

`slapt-get --upgrade`

- Cerca pacchetti per nome del pacchetto, set del disco o versione:

`slapt-get --search {{ricerca}}`

- Mostra informazioni su un pacchetto:

`slapt-get --show {{pacchetto}}`
