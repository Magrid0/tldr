# systemd-dissect

> Ispeziona e interagisce con immagini disco del filesystem del sistema operativo, in particolare Discoverable Disk Images (DDI).
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-dissect.html>.

- Mostra le informazioni generali sull'immagine del sistema operativo:

`systemd-dissect {{percorso/dell/immagine.raw}}`

- Monta un'immagine del sistema operativo:

`systemd-dissect {{[-m|--mount]}} {{percorso/dell/immagine.raw}} {{/mnt/immagine}}`

- Smonta un'immagine del sistema operativo:

`systemd-dissect {{[-u|--umount]}} {{/mnt/immagine}}`

- Elenca i file in un'immagine:

`systemd-dissect {{[-l|--list]}} {{percorso/dell/immagine.raw}}`

- Collega un'immagine del sistema operativo a un dispositivo a blocchi loopback allocato automaticamente e ne stampa il percorso:

`systemd-dissect --attach {{percorso/dell/immagine.raw}}`

- Scollega un'immagine del sistema operativo da un dispositivo a blocchi loopback:

`systemd-dissect --detach {{percorso/del/dispositivo}}`
