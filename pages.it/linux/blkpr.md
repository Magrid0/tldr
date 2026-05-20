# blkpr

> Registra, riserva, rilascia, previene e cancella prenotazioni persistenti su un dispositivo a blocchi che supporta prenotazioni persistenti.
> Maggiori informazioni: <https://manned.org/blkpr>.

- Registra (comando) una nuova prenotazione con una data chiave su un dato dispositivo:

`blkpr {{[-c|--command]}} register {{[-k|--key]}} {{reservation_key}} {{path/to/device}}`

- Imposta il tipo di una prenotazione esistente ad accesso esclusivo:

`blkpr {{[-c|--command]}} reserve {{[-k|--key]}} {{reservation_key}} {{[-t|--type]}} exclusive-access {{path/to/device}}`

- Previene la prenotazione esistente con una data chiave e la sostituisce con una nuova prenotazione:

`blkpr {{[-c|--command]}} preempt {{[-K|--oldkey]}} {{old_key}} {{[-k|--key]}} {{new_key}} {{[-t|--type]}} write-exclusive {{path/to/device}}`

- Rilascia una prenotazione con una data chiave e tipo su un dato dispositivo:

`blkpr {{[-c|--command]}} release {{[-k|--key]}} {{reservation_key}} {{[-t|--type]}} {{reservation_type}} {{path/to/device}}`

- Cancella tutte le prenotazioni da un dato dispositivo:

`blkpr {{[-c|--command]}} clear {{[-k|--key]}} {{key}} {{path/to/device}}`
