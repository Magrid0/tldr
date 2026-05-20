# sport

> Cerca e installa SlackBuilds.
> Maggiori informazioni: <http://slackermedia.info/handbook/doku.php?id=slackbuilds>.

- Scarica la lista degli SlackBuilds per eseguire `sport` per la prima volta:

`sudo mkdir {{[-p|--parents]}} /usr/ports && sudo rsync {{[-av|--archive --verbose]}} rsync://slackbuilds.org /slackbuilds/$(awk '{print $2}' /etc/slackware-version)/ /usr/ports/`

- Scarica eventuali aggiornamenti all'albero del sistema via `rsync`:

`sudo sport rsync`

- Cerca un pacchetto per nome:

`sport search "{{parola_chiave}}"`

- Controlla se un pacchetto è installato:

`sport check {{pacchetto}}`

- Mostra i file README e `.info` di un pacchetto:

`sport cat {{pacchetto}}`

- Installa un pacchetto una volta risolte le dipendenze:

`sudo sport install {{pacchetto}}`

- Installa un elenco di pacchetti da un file (formato: pacchetti separati da spazi):

`sudo sport install $(< {{percorso/della/lista}})`
