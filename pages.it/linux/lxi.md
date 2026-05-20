# lxi

> Controlla strumenti compatibili LXI come oscilloscopi.
> Maggiori informazioni: <https://github.com/lxi-tools/lxi-tools#32-lxi>.

- Scopri dispositivi LXI sulle reti disponibili:

`lxi discover`

- Cattura uno screenshot, rilevando automaticamente un plugin:

`lxi screenshot {{[-a|--address]}} {{ip_address}}`

- Cattura uno screenshot usando un plugin specificato:

`lxi screenshot {{[-a|--address]}} {{ip_address}} {{[-p|--plugin]}} {{rigol-1000z}}`

- Invia un comando SCPI a uno strumento:

`lxi scpi {{[-a|--address]}} {{ip_address}} "{{*IDN?}}"`

- Esegue un benchmark per le prestazioni di richiesta e risposta:

`lxi benchmark {{[-a|--address]}} {{ip_address}}`
