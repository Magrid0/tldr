# objcopy

> Copia il contenuto di un file oggetto in un altro file.
> Maggiori informazioni: <https://manned.org/objcopy>.

- Copia dati in un altro file:

`objcopy {{percorso/del/file_sorgente}} {{percorso/del/file_destinazione}}`

- Traduce file oggetto da un formato all'altro:

`objcopy --input-target={{formato_input}} --output-target {{formato_output}} {{percorso/del/file_sorgente}} {{percorso/del/file_destinazione}}`

- Rimuove tutte le informazioni sui simboli dal file:

`objcopy --strip-all {{percorso/del/file_sorgente}} {{percorso/del/file_destinazione}}`

- Rimuove le informazioni di debug dal file:

`objcopy --strip-debug {{percorso/del/file_sorgente}} {{percorso/del/file_destinazione}}`

- Copia una sezione specifica dal file sorgente al file di destinazione:

`objcopy --only-section {{sezione}} {{percorso/del/file_sorgente}} {{percorso/del/file_destinazione}}`
