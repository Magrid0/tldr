# scrot

> Utility di cattura dello schermo.
> Maggiori informazioni: <https://manned.org/scrot>.

- Cattura uno screenshot e lo salva nella directory corrente con la data corrente come nome file:

`scrot`

- Cattura uno screenshot e lo salva come `capture.png`:

`scrot capture.png`

- Cattura uno screenshot in modo interattivo:

`scrot {{[-s|--select]}}`

- Cattura uno screenshot in modo interattivo senza uscire alla pressione di tasti, premi `<Esc>` per uscire:

`scrot {{[-is|--ignorekeyboard --select]}}`

- Cattura uno screenshot in modo interattivo delimitando la regione con una linea colorata:

`scrot {{[-s|--select]}} {{[-l|--line]}} color={{colore_x11|colore_rgb}}`

- Cattura uno screenshot dalla finestra attualmente focalizzata:

`scrot {{[-u|--focused]}}`

- Mostra un conto alla rovescia di 10 secondi prima di catturare uno screenshot:

`scrot {{[-c|--count]}} {{[-d|--delay]}} 10`
