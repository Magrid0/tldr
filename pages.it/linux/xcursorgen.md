# xcursorgen

> Crea un file cursore X da una collezione di PNG.
> Se `--prefix` viene omesso, i file immagine devono trovarsi nella directory di lavoro corrente.
> Maggiori informazioni: <https://manned.org/xcursorgen>.

- Crea un file cursore X usando un file di configurazione:

`xcursorgen {{path/to/config.cursor}} {{path/to/file_output}}`

- Crea un file cursore X usando un file di configurazione e specifica il percorso dei file immagine:

`xcursorgen --prefix {{path/to/directory_immagini}}/ {{path/to/config.cursor}} {{path/to/file_output}}`

- Crea un file cursore X usando un file di configurazione e scrive l'output su `stdout`:

`xcursorgen {{path/to/config.cursor}}`
