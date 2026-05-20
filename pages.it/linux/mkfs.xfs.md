# mkfs.xfs

> Crea un filesystem XFS all'interno di una partizione.
> Maggiori informazioni: <https://manned.org/mkfs.xfs>.

- Crea un filesystem XFS all'interno della partizione Y sul dispositivo X:

`sudo mkfs.xfs {{/dev/sdXY}}`

- Crea un filesystem XFS con un'etichetta di volume:

`sudo mkfs.xfs -L {{volume_label}} {{/dev/sdXY}}`
