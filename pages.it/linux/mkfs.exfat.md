# mkfs.exfat

> Crea un filesystem exFAT all'interno di una partizione.
> Maggiori informazioni: <https://manned.org/mkfs.exfat>.

- Crea un filesystem exFAT all'interno della partizione Y sul dispositivo X:

`sudo mkfs.exfat {{/dev/sdXY}}`

- Crea un filesystem con un nome di volume:

`sudo mkfs.exfat {{[-L|--volume-label]}} {{volume_name}} {{/dev/sdXY}}`

- Crea un filesystem con un ID volume:

`sudo mkfs.exfat {{[-U|--volume-guid]}} {{volume_id}} {{/dev/sdXY}}`
