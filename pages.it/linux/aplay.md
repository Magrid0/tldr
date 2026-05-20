# aplay

> Lettore audio per il driver della scheda audio ALSA.
> Maggiori informazioni: <https://manned.org/aplay>.

- Riproduce un file specifico (la frequenza di campionamento, la profondità di bit, ecc. verranno determinati automaticamente per il formato del file):

`aplay {{path/to/file}}`

- Riproduce i primi 10 secondi di un file specifico a 2500 Hz:

`aplay {{[-d|--duration]}} {{10}} {{[-r|--rate]}} {{2500}} {{path/to/file}}`

- Riproduce il file raw come file `.au` a 22050 Hz, mono, 8 bit, Mu-Law:

`aplay {{[-c|--channels]}} {{1}} {{[-t|--file-type]}} {{raw}} {{[-r|--rate]}} {{22050}} {{[-f|--format]}} {{mu_law}} {{path/to/file}}`

- Elenca i dispositivi audio disponibili:

`aplay {{[-l|--list-devices]}}`
