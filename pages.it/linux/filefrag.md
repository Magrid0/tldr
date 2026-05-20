# filefrag

> Segnala quanto è frammentato un file.
> Maggiori informazioni: <https://manned.org/filefrag>.

- Mostra un report per uno o più file:

`filefrag {{path/to/file1 path/to/file2 ...}}`

- Mostra un report utilizzando una dimensione del blocco di 1024 byte:

`filefrag -k {{path/to/file}}`

- Mostra un report utilizzando una specifica dimensione del blocco:

`filefrag -b{{1024|1K|1M|1G|...}} {{path/to/file}}`

- Sincronizza il file prima di richiedere la mappatura:

`filefrag -s {{path/to/file1 path/to/file2 ...}}`

- Mostra la mappatura degli attributi estesi:

`filefrag -x {{path/to/file1 path/to/file2 ...}}`

- Mostra un report con informazioni dettagliate:

`filefrag -v {{path/to/file1 path/to/file2 ...}}`
