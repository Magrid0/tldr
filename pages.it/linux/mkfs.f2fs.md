# mkfs.f2fs

> Crea un filesystem F2FS all'interno di una partizione.
> Maggiori informazioni: <https://manned.org/mkfs.f2fs>.

- Crea un filesystem F2FS all'interno della partizione Y sul dispositivo X:

`sudo mkfs.f2fs {{/dev/sdXY}}`

- Crea un filesystem F2FS con un'etichetta di volume:

`sudo mkfs.f2fs -l {{volume_label}} {{/dev/sdXY}}`
