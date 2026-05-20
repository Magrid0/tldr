# mkfs.ntfs

> Crea un filesystem NTFS all'interno di una partizione.
> Maggiori informazioni: <https://manned.org/mkfs.ntfs>.

- Crea un filesystem NTFS all'interno della partizione Y sul dispositivo X:

`sudo mkfs.ntfs {{/dev/sdXY}}`

- Crea un filesystem con un'etichetta di volume:

`sudo mkfs.ntfs {{[-L|--label]}} {{volume_label}} {{/dev/sdXY}}`

- Crea un filesystem con UUID specifico:

`sudo mkfs.ntfs {{[-U|--with-uuid]}} {{UUID}} {{/dev/sdXY}}`
