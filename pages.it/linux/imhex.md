# imhex

> Editor esadecimale per reverse engineer e programmatori.
> Maggiori informazioni: <https://docs.werwolv.net/imhex/>.

- Apre un file in ImHex:

`imhex {{path/to/file}}`

- Crea un nuovo file vuoto:

`imhex --new`

- Apre un file nell'istanza ImHex in esecuzione e seleziona un intervallo di byte (offset in esadecimale):

`imhex --open {{path/to/file}} --select {{0xstart_offset}} {{0xend_offset}}`

- Mostra informazioni su un file:

`imhex --file-info {{path/to/file}}`

- Calcola l'hash di un file usando un algoritmo specifico (`md5`, `sha1`, `sha224`, `sha256`, `sha384`, `sha512`):

`imhex --hash {{algorithm}} {{path/to/file}}`

- Genera un dump esadecimale di un file:

`imhex --hexdump {{path/to/file}}`

- Mostra versione:

`imhex --version`
