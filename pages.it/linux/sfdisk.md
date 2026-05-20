# sfdisk

> Mostra o manipola una tabella delle partizioni del disco.
> Maggiori informazioni: <https://manned.org/sfdisk>.

- Salva il layout delle partizioni in un file:

`sudo sfdisk {{[-d|--dump]}} {{/dev/sdX}} > {{percorso/del/file.dump}}`

- Ripristina un layout di partizioni:

`sudo sfdisk < {{percorso/del/file.dump}} {{/dev/sdX}}`

- Imposta il tipo di una partizione:

`sudo sfdisk --part-type {{/dev/sdX}} {{numero_partizione}} {{swap}}`

- Elimina una partizione:

`sudo sfdisk --delete {{/dev/sdX}} {{numero_partizione}}`

- Mostra aiuto:

`sfdisk {{[-h|--help]}}`
