# wajig

> Strumento di supporto al sistema semplificato tutto-in-uno per sistemi basati su Debian.
> Maggiori informazioni: <https://togaware.com/linux/survivor/wajig.html>.

- Aggiorna la lista dei pacchetti e delle versioni disponibili:

`wajig update`

- Installa un pacchetto o aggiornalo all'ultima versione disponibile:

`wajig install {{pacchetto}}`

- Rimuovi un pacchetto e i suoi file di configurazione:

`wajig purge {{pacchetto}}`

- Esegui un aggiornamento seguito da un dist-upgrade:

`wajig daily-upgrade`

- Mostra le dimensioni dei pacchetti installati:

`wajig sizes`

- Elenca la versione e la distribuzione per tutti i pacchetti installati:

`wajig versions`

- Elenca le versioni dei pacchetti aggiornabili:

`wajig toupgrade`

- Mostra i pacchetti che hanno qualche forma di dipendenza dal pacchetto specificato:

`wajig dependents {{pacchetto}}`
