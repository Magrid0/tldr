# systemd-mount

> Stabilisce e distrugge punti di montaggio o auto-montaggio transitori.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-mount.html>.

- Monta un filesystem (immagine o dispositivo a blocchi) su `/run/media/system/LABEL` dove LABEL è l'etichetta del filesystem o il nome del dispositivo se non c'è etichetta:

`systemd-mount {{percorso/del/file_o_dispositivo}}`

- Monta un filesystem (immagine o dispositivo a blocchi) in una posizione specifica:

`systemd-mount {{percorso/del/file_o_dispositivo}} {{percorso/del/punto_di_mount}}`

- Elenca tutti i dispositivi a blocchi locali noti con filesystem che possono essere montati:

`systemd-mount --list`

- Crea un punto di auto-montaggio che monta il filesystem effettivo al momento del primo accesso:

`systemd-mount --automount yes {{percorso/del/file_o_dispositivo}}`

- Smonta uno o più dispositivi:

`systemd-mount {{[-u|--umount]}} {{percorso/del/punto_di_mount_o_dispositivo1 percorso/del/punto_di_mount_o_dispositivo2 ...}}`

- Monta un filesystem (immagine o dispositivo a blocchi) con un tipo di filesystem specifico:

`systemd-mount {{[-t|--type]}} {{tipo_filesystem}} {{percorso/del/file_o_dispositivo}} {{percorso/del/punto_di_mount}}`

- Monta un filesystem (immagine o dispositivo a blocchi) con opzioni di mount aggiuntive:

`systemd-mount {{[-o|--options]}} {{opzioni_mount}} {{percorso/del/file_o_dispositivo}} {{percorso/del/punto_di_mount}}`
