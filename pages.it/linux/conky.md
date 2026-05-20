# conky

> Monitor di sistema leggero per X.
> Maggiori informazioni: <https://github.com/brndnmtthws/conky>.

- Avvia con la configurazione predefinita integrata:

`conky`

- Crea una nuova configurazione predefinita:

`conky {{[-C|--print-config]}} > ~/.conkyrc`

- Avvia Conky con un file di configurazione specifico:

`conky {{[-c|--config]}} {{path/to/config}}`

- Avvia in background (demone):

`conky {{[-d|--daemonize]}}`

- Allinea Conky sul desktop:

`conky {{[-a|--alignment]}} {{top|bottom|middle}}_{{left|right|middle}}`

- Attende 5 secondi all'avvio prima di lanciarsi:

`conky {{[-p|--pause]}} {{5}}`
