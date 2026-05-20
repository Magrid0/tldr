# compress

> Comprime i file utilizzando il comando Unix `compress`.
> Maggiori informazioni: <https://manned.org/compress>.

- Comprime file specifici:

`compress {{path/to/file1 path/to/file2 ...}}`

- Comprime file specifici, ignora quelli inesistenti:

`compress -f {{path/to/file1 path/to/file2 ...}}`

- Specifica i bit di compressione massimi (9-16 bit):

`compress -b {{bits}}`

- Scrive su `stdout` (nessun file viene modificato):

`compress -c {{path/to/file}}`

- Decomprime i file (funziona come `uncompress`):

`compress -d {{path/to/file}}`

- Mostra la percentuale di compressione:

`compress -v {{path/to/file}}`
