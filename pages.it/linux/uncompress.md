# uncompress

> Decomprimi file compressi usando il comando Unix `compress`.
> Maggiori informazioni: <https://manned.org/uncompress>.

- Decomprimi file specifici:

`uncompress {{percorso/del/file1.Z percorso/del/file2.Z ...}}`

- Decomprimi file specifici ignorando quelli inesistenti:

`uncompress -f {{percorso/del/file1.Z percorso/del/file2.Z ...}}`

- Scrivi su `stdout` (nessun file viene modificato e nessun file `.Z` viene creato):

`uncompress -c {{percorso/del/file1.Z percorso/del/file2.Z ...}}`

- Modalità verbosa (scrivi su `stderr` la percentuale di riduzione o espansione):

`uncompress -v {{percorso/del/file1.Z percorso/del/file2.Z ...}}`
