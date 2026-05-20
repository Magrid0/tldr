# blkdiscard

> Elimina i settori del dispositivo su dispositivi di archiviazione. Utile per SSD.
> Maggiori informazioni: <https://manned.org/blkdiscard>.

- Elimina tutti i settori su un dispositivo, rimuovendo tutti i dati:

`blkdiscard {{/dev/device}}`

- Elimina in modo sicuro tutti i blocchi su un dispositivo, rimuovendo tutti i dati:

`blkdiscard {{[-s|--secure]}} {{/dev/device}}`

- Elimina i primi 100 MB di un dispositivo:

`blkdiscard {{[-l|--length]}} {{100MB}} {{/dev/device}}`
