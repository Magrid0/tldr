# mkfs.bcachefs

> Crea un filesystem `bcachefs` all'interno di una partizione.
> Vedi anche: `bcachefs`.
> Maggiori informazioni: <https://bcachefs-docs.readthedocs.io/en/latest/mgmt-formatting.html>.

- Crea un filesystem `bcachefs` all'interno della partizione `Y` su un dispositivo `X`:

`sudo mkfs.bcachefs {{/dev/sdXY}}`

- Crea un filesystem `bcachefs` con un'etichetta di volume:

`sudo mkfs.bcachefs {{[-L|--fs_label]}} {{volume_label}} {{/dev/sdXY}}`
