# mkfs.ext4

> Crea un filesystem ext4 all'interno di una partizione.
> Maggiori informazioni: <https://manned.org/mkfs.ext4>.

- Crea un filesystem ext4 all'interno della partizione Y sul dispositivo X:

`sudo mkfs.ext4 {{/dev/sdXY}}`

- Crea un filesystem ext4 con un'etichetta di volume:

`sudo mkfs.ext4 -L {{volume_label}} {{/dev/sdXY}}`

- Crea un filesystem ext4 di proprietà di un utente e gruppo specifici:

`sudo mkfs.ext4 -E root_owner={{uid}}:{{gid}} {{/dev/sdXY}}`
