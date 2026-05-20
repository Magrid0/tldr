# lvmpolld

> Demone di polling LVM che supervisiona le operazioni LVM di lunga durata.
> Maggiori informazioni: <https://manned.org/lvmpolld>.

- Avvia il demone in primo piano:

`lvmpolld {{[-f|--foreground]}}`

- Avvia in primo piano con logging di debug:

`lvmpolld {{[-f|--foreground]}} {{[-l|--log]}} debug`

- Imposta il timeout di spegnimento per inattività (secondi):

`lvmpolld {{[-t|--timeout]}} {{300}}`

- Usa un percorso socket personalizzato:

`lvmpolld {{[-s|--socket]}} {{/tmp/lvmpolld.socket}}`

- Usa un file PID personalizzato:

`lvmpolld {{[-p|--pidfile]}} {{/tmp/lvmpolld.pid}}`

- Scarica lo stato corrente:

`lvmpolld --dump`
