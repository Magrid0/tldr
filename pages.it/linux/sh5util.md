# sh5util

> Unisce file HDF5 prodotti dal plugin `sacct_gather_profile`.
> Maggiori informazioni: <https://slurm.schedmd.com/sh5util.html>.

- Unisce i file HDF5 prodotti su ogni nodo allocato per il job o step specificato:

`sh5util {{[-j|--jobs]}} {{id_job|id_job.id_step}}`

- Estrae una o più serie di dati da un file di job unito:

`sh5util {{[-j|--jobs]}} {{id_job|id_job.id_step}} {{[-E|--extract]}} {{[-i|--input]}} {{percorso/del/file.h5}} {{[-s|--series]}} {{Energy|Filesystem|Network|Task}}`

- Estrae un elemento di dati da tutti i nodi in un file di job unito:

`sh5util {{[-j|--jobs]}} {{id_job|id_job.id_step}} {{[-I|--item-extract]}} {{[-s|--series]}} {{Energy|Filesystem|Network|Task}} {{[-d|--data]}} {{elemento_dato}}`
