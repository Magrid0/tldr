# fold

> Suddivide le righe lunghe per dispositivi di output a larghezza fissa.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/fold-invocation.html>.

- Suddivide le righe a una larghezza fissa:

`fold {{[-w|--width]}} {{width}} {{path/to/file}}`

- Conta la larghezza in byte (l'impostazione predefinita è contare in colonne):

`fold {{[-b|--bytes]}} {{[-w|--width]}} {{width_in_bytes}} {{path/to/file}}`

- Spezza la riga dopo lo spazio vuoto più a destra entro il limite di larghezza:

`fold {{[-s|--spaces]}} {{[-w|--width]}} {{width}} {{path/to/file}}`
