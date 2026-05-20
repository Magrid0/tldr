# partprobe

> Notifica al kernel del sistema operativo i cambiamenti alla tabella delle partizioni.
> Maggiori informazioni: <https://manned.org/partprobe>.

- Notifica al kernel del sistema operativo i cambiamenti alla tabella delle partizioni:

`sudo partprobe`

- Notifica al kernel i cambiamenti alla tabella delle partizioni e mostra un riepilogo dei dispositivi e delle loro partizioni:

`sudo partprobe {{[-s|--summary]}}`

- Mostra un riepilogo dei dispositivi e delle loro partizioni senza notificare il kernel:

`sudo partprobe {{[-s|--summary]}} {{[-d|--dry-run]}}`
