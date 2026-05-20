# col

> Filtra i caratteri di avanzamento riga inversi dall'input.
> Maggiori informazioni: <https://manned.org/col>.

- Filtra i caratteri di avanzamento riga inversi dall'input:

`{{command}} | col`

- Filtra i caratteri di avanzamento riga inversi e restituisce l'output con spazi invece di tabulazioni:

`{{command}} | col {{[-x|--spaces]}}`

- Rimuove i backspace, restituisce solo l'ultimo carattere scritto in ogni posizione:

`{{command}} | col {{[-b|--no-backspaces]}}`

- Specifica una dimensione del buffer con un numero specifico di righe:

`{{command}} | col {{[-l|--lines]}} {{num}}`

- Formatta una pagina di manuale per la visualizzazione con `less`:

`man ls | col {{[-b|--no-backspaces]}} | less`

- Elabora un file con caratteri di avanzamento riga inversi e salva l'output pulito:

`cat {{path/to/input_file}} | col {{[-x|--spaces]}} > {{output_file}}`
