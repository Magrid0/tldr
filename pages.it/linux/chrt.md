# chrt

> Manipola gli attributi in tempo reale di un processo.
> Maggiori informazioni: <https://manned.org/chrt>.

- Mostra gli attributi di un processo:

`chrt {{[-p|--pid]}} {{PID}}`

- Mostra gli attributi di tutti i thread di un processo:

`chrt {{[-a|--all-tasks]}} {{[-p|--pid]}} {{PID}}`

- Mostra i valori di priorità minimi/massimi utilizzabili con `chrt`:

`chrt {{[-m|--max]}}`

- Imposta la priorità di scheduling di un processo:

`chrt {{[-p|--pid]}} {{priority}} {{PID}}`

- Imposta la politica di scheduling di un processo:

`chrt --{{deadline|idle|batch|rr|fifo|other}} {{[-p|--pid]}} {{priority}} {{PID}}`
