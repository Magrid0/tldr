# blkid

> Elenca tutte le partizioni riconosciute e il loro Universally Unique Identifier (UUID).
> Maggiori informazioni: <https://manned.org/blkid>.

- Elenca tutte le partizioni:

`sudo blkid`

- Elenca tutte le partizioni in una tabella, inclusi i punti di montaggio correnti:

`sudo blkid {{[-o|--output]}} list`

- Ottiene l'UUID del filesystem su una partizione:

`sudo blkid {{[-s|--match-tag]}} UUID {{[-o|--output]}} value {{/dev/sdXY}}`
