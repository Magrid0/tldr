# deb-get

> `apt-get` functionality for `.deb` packages published in third party repositories or via direct download.
> Funziona con distribuzioni Linux che usano `apt-get`.
> Maggiori informazioni: <https://github.com/wimpysworld/deb-get>.

- Aggiorna l'elenco dei pacchetti e delle versioni disponibili:

`deb-get update`

- Cerca un dato pacchetto:

`deb-get search {{package}}`

- Mostra informazioni su un pacchetto:

`deb-get show {{package}}`

- Installa un pacchetto o lo aggiorna all'ultima versione disponibile:

`deb-get install {{package}}`

- Rimuove un pacchetto (usando `purge` rimuove anche i file di configurazione):

`deb-get remove {{package}}`

- Aggiorna tutti i pacchetti installati alle versioni più recenti disponibili:

`deb-get upgrade`

- Elenca tutti i pacchetti disponibili:

`deb-get list`
