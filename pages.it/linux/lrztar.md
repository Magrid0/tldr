# lrztar

> Un wrapper per `lrzip` per semplificare la compressione di directory.
> Vedi anche: `tar`, `lrzuntar`, `lrunzip`.
> Maggiori informazioni: <https://manned.org/lrztar>.

- Archivia una directory con tar, poi comprime:

`lrztar {{path/to/directory}}`

- Come sopra, con ZPAQ - compressione estrema, ma molto lento:

`lrztar {{[-z|--zpaq]}} {{path/to/directory}}`

- Specifica il file di output:

`lrztar {{[-o|--outfile]}} {{path/to/file}} {{path/to/directory}}`

- Sovrascrive il numero di thread del processore da usare:

`lrztar {{[-p|--threads]}} {{8}} {{path/to/directory}}`

- Forza la sovrascrittura dei file esistenti:

`lrztar {{[-f|--force]}} {{path/to/directory}}`
