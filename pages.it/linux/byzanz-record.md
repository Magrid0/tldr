# byzanz-record

> Registra lo schermo.
> Maggiori informazioni: <https://manned.org/byzanz-record>.

- Registra lo schermo e scrive la registrazione in un file (per impostazione predefinita, `byzanz-record` registra solo per 10 secondi):

`byzanz-record {{path/to/file.[byzanz|flv|gif|ogg|ogv|webm]}}`

- Mostra informazioni durante e dopo la registrazione:

`byzanz-record {{[-v|--verbose]}} {{path/to/file.[byzanz|flv|gif|ogg|ogv|webm]}}`

- Registra lo schermo per un minuto:

`byzanz-record {{[-d|--duration]}} 60 {{path/to/file.[byzanz|flv|gif|ogg|ogv|webm]}}`

- Ritarda la registrazione di 10 secondi:

`byzanz-record --delay 10 {{path/to/file.[byzanz|flv|gif|ogg|ogv|webm]}}`
