# umount

> Scollega un filesystem dal suo punto di montaggio, rendendolo non più accessibile.
> Un filesystem non può essere smontato quando è in uso.
> Maggiori informazioni: <https://manned.org/umount.8>.

- Smonta un filesystem passando il percorso al dispositivo di origine da cui è montato:

`sudo umount {{percorso/del/file_dispositivo}}`

- Smonta un filesystem passando il percorso di destinazione in cui è montato:

`sudo umount {{percorso/della/directory_montata}}`

- Quando lo smontaggio fallisce, prova a rimontare il filesystem in sola lettura:

`sudo umount {{[-r|--read-only]}} {{percorso/della/directory_montata}}`

- Smonta ricorsivamente ogni directory specificata:

`sudo umount {{[-R|--recursive]}} {{percorso/della/directory_montata}}`

- Smonta tutti i filesystem montati (eccetto il filesystem `proc`):

`sudo umount {{[-a|--all]}}`
