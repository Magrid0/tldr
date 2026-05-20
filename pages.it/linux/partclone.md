# partclone

> Copia e ripristina partizioni da e verso un'immagine ignorando i blocchi vuoti.
> Maggiori informazioni: <https://manned.org/partclone>.

- Copia una partizione in un'immagine:

`sudo partclone.{{ext4|btrfs|fat32|xfs|...}} {{[-c|--clone]}} {{[-s|--source]}} {{/dev/sdXY}} {{[-o|--output]}} {{percorso/backup.img}}`

- Ripristina una partizione da un'immagine:

`sudo partclone.{{ext4|btrfs|fat32|xfs|...}} {{[-c|--clone]}} {{[-s|--source]}} {{percorso/backup.img}} {{[-o|--output]}} {{/dev/sdXY}}`

- Mostra aiuto:

`partclone.{{ext4|btrfs|fat32|xfs|...}} {{[-h|--help]}}`
