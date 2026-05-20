# e2undo

> Riproduce i log di annullamento per un filesystem ext2/ext3/ext4.
> Può essere utilizzato per annullare un'operazione fallita da un programma e2fsprogs.
> Maggiori informazioni: <https://manned.org/e2undo>.

- Mostra le informazioni su un file di annullamento specifico:

`e2undo -h {{path/to/file_annullamento}} {{/dev/sdXN}}`

- Esegue una simulazione e mostra i blocchi candidati per la riproduzione:

`e2undo -nv {{path/to/file_annullamento}} {{/dev/sdXN}}`

- Esegue un'operazione di annullamento:

`e2undo {{path/to/file_annullamento}} {{/dev/sdXN}}`

- Esegue un'operazione di annullamento e mostra informazioni [v]erbose:

`e2undo -v {{path/to/file_annullamento}} {{/dev/sdXN}}`

- Scrive il vecchio contenuto del blocco in un file di annullamento prima di sovrascrivere un blocco del filesystem:

`e2undo -z {{path/to/file.e2undo}} {{path/to/file_annullamento}} {{/dev/sdXN}}`
