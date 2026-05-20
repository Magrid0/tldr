# ptx

> Genera un indice permutato di parole da file di testo.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/ptx-invocation.html>.

- Genera un indice permutato dove il primo campo di ogni riga è un riferimento di indice:

`ptx {{[-r|--references]}} {{percorso/del/file}}`

- Genera un indice permutato con riferimenti di indice generati automaticamente:

`ptx {{[-A|--auto-reference]}} {{percorso/del/file}}`

- Genera un indice permutato con larghezza fissa:

`ptx {{[-w|--width]}} {{larghezza_in_colonne}} {{percorso/del/file}}`

- Genera un indice permutato con una lista di parole filtrate:

`ptx {{[-o|--only-file]}} {{percorso/del/filtro}} {{percorso/del/file}}`

- Genera un indice permutato con comportamenti in stile SYSV:

`ptx {{[-G|--traditional]}} {{percorso/del/file}}`
