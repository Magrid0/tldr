# pidstat

> Mostra l'utilizzo delle risorse di sistema, inclusi CPU, memoria, I/O, ecc.
> Maggiori informazioni: <https://manned.org/pidstat>.

- Mostra statistiche CPU a intervalli di 2 secondi per 10 volte:

`pidstat {{2}} {{10}}`

- Mostra page fault e utilizzo memoria:

`pidstat -r`

- Mostra l'utilizzo input/output per ID processo:

`pidstat -d`

- Mostra informazioni su un PID specifico:

`pidstat -p {{PID}}`

- Mostra statistiche memoria per tutti i processi il cui nome comando include "fox" o "bird":

`pidstat -C "{{fox|bird}}" -r -p ALL`
