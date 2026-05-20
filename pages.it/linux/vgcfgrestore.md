# vgcfgrestore

> Ripristina la configurazione del volume group (non i dati utente) da un file di backup di testo prodotto da `vgcfgbackup`.
> Maggiori informazioni: <https://manned.org/vgcfgrestore>.

- Ripristina i metadati VG dall'ultimo backup:

`sudo vgcfgrestore {{nome_vg}}`

- Ripristina i metadati VG da un file di backup specificato:

`sudo vgcfgrestore {{[-f|--file]}} {{percorso/del/file}} {{nome_vg}}`

- Elenca tutti i backup dei metadati VG:

`sudo vgcfgrestore {{[-l|--list]}} {{nome_vg}}`

- Elenca un file di backup dei metadati VG:

`sudo vgcfgrestore {{[-l|--list]}} {{[-f|--file]}} {{percorso/del/file}} {{nome_vg}}`
