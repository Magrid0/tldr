# dumpe2fs

> Stampa le informazioni del superblocco e dei gruppi di blocchi per filesystem ext2/ext3/ext4.
> Smonta la partizione prima di eseguire questo comando usando `umount dispositivo`.
> Maggiori informazioni: <https://manned.org/dumpe2fs>.

- Mostra le informazioni del filesystem ext2, ext3 e ext4:

`dumpe2fs {{/dev/sdXN}}`

- Mostra i blocchi riservati come danneggiati nel filesystem:

`dumpe2fs -b {{/dev/sdXN}}`

- Forza la visualizzazione delle informazioni del filesystem anche con flag di feature non riconoscibili:

`dumpe2fs -f {{/dev/sdXN}}`

- Mostra solo le informazioni del superblocco e non i dettagli dei descrittori dei gruppi di blocchi:

`dumpe2fs -h {{/dev/sdXN}}`

- Stampa i numeri di blocco delle informazioni dettagliate del gruppo in formato esadecimale:

`dumpe2fs -x {{/dev/sdXN}}`
