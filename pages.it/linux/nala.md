# nala

> Utilità di gestione pacchetti con una formattazione migliore.
> Interfaccia front-end per l'API `python-apt`.
> Maggiori informazioni: <https://gitlab.com/volian/nala>.

- Installa un pacchetto, o lo aggiorna all'ultima versione disponibile:

`sudo nala install {{pacchetto}}`

- Rimuove un pacchetto:

`sudo nala remove {{pacchetto}}`

- Rimuove un pacchetto e i suoi file di configurazione:

`nala purge {{pacchetto}}`

- Cerca tra nomi e descrizioni dei pacchetti usando una parola, `regex` (predefinito) o glob:

`nala search "{{pattern}}"`

- Aggiorna la lista dei pacchetti disponibili e aggiorna il sistema:

`sudo nala upgrade`

- Rimuove tutti i pacchetti e le dipendenze inutilizzati dal sistema:

`sudo nala autoremove`

- Recupera mirror veloci per migliorare la velocità di download:

`sudo nala fetch`

- Mostra la cronologia di tutte le transazioni:

`nala history`
