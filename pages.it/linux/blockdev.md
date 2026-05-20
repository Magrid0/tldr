# blockdev

> Gestisce, interroga e manipola dispositivi a blocchi.
> Maggiori informazioni: <https://manned.org/blockdev>.

- Stampa un report per tutti i dispositivi:

`sudo blockdev --report`

- Stampa un report per un dispositivo specifico:

`sudo blockdev --report {{/dev/sdXY}}`

- Ottiene la dimensione di un dispositivo in settori da 512 byte:

`sudo blockdev --getsz {{/dev/sdXY}}`

- Imposta la modalità sola lettura:

`sudo blockdev --setro {{/dev/sdXY}}`

- Imposta la modalità lettura-scrittura:

`sudo blockdev --setrw {{/dev/sdXY}}`

- Svuota i buffer:

`sudo blockdev --flushbufs {{/dev/sdXY}}`

- Ottiene la dimensione del blocco fisico:

`sudo blockdev --getpbsz {{/dev/sdXY}}`

- Imposta il valore di read-ahead a 128 settori:

`sudo blockdev --setra 128 {{/dev/sdXY}}`
