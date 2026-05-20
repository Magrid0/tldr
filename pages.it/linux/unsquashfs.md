# unsquashfs

> Decomprime, estrae ed elenca i file nei filesystem squashfs.
> Maggiori informazioni: <https://manned.org/unsquashfs>.

- Estrae un filesystem squashfs in `squashfs-root` nella directory di lavoro corrente:

`unsquashfs {{filesystem.squashfs}}`

- Estrae un filesystem squashfs nella directory specificata:

`unsquashfs {{[-d|-dest]}} {{percorso/della/directory}} {{filesystem.squashfs}}`

- Mostra i nomi dei file durante l'estrazione:

`unsquashfs {{[-i|-info]}} {{filesystem.squashfs}}`

- Mostra i nomi dei file e i loro attributi durante l'estrazione:

`unsquashfs {{[-li|-linfo]}} {{filesystem.squashfs}}`

- Elenca i file all'interno del filesystem squashfs (senza estrarre):

`unsquashfs {{[-l|-ls]}} {{filesystem.squashfs}}`

- Elenca i file e i loro attributi all'interno del filesystem squashfs (senza estrarre):

`unsquashfs {{[-ll|-lls]}} {{filesystem.squashfs}}`
