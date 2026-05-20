# mkfs.fat

> Crea un filesystem MS-DOS all'interno di una partizione.
> Maggiori informazioni: <https://manned.org/mkfs.fat>.

- Crea un filesystem FAT all'interno della partizione `Y` sul dispositivo `X`:

`sudo mkfs.fat {{/dev/sdXY}}`

- Crea un filesystem con un nome di volume:

`sudo mkfs.fat -n {{volume_name}} {{/dev/sdXY}}`

- Crea un filesystem con un ID volume:

`sudo mkfs.fat -i {{volume_id}} {{/dev/sdXY}}`

- Usa 4 invece di 2 tabelle di allocazione file:

`sudo mkfs.fat -f 4 {{/dev/sdXY}}`

- Specifica il tipo di filesystem:

`sudo mkfs.fat -F {{12|16|32}} {{/dev/sdXY}}`
