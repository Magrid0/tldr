# mkfs.cramfs

> Crea un filesystem ROM all'interno di una partizione.
> Maggiori informazioni: <https://manned.org/mkfs.cramfs>.

- Crea un filesystem ROM da una directory all'interno della partizione Y sul dispositivo X:

`sudo mkfs.cramfs {{path/to/directory}} {{/dev/sdXY}}`

- Crea un filesystem ROM con un nome di volume:

`sudo mkfs.cramfs -n {{volume_name}} {{path/to/directory}} {{/dev/sdXY}}`
