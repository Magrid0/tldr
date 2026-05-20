# strip

> Rimuove i simboli da eseguibili o file oggetto.
> Maggiori informazioni: <https://manned.org/strip>.

- Sostituisce il file di input con la sua versione senza simboli:

`strip {{percorso/del/file}}`

- Rimuove i simboli da un file, salvando l'output in un file specifico:

`strip {{percorso/del/file_input}} -o {{percorso/del/file_output}}`

- Rimuove solo i simboli di debug:

`strip {{[-d|--strip-debug]}} {{percorso/del/file.o}}`
