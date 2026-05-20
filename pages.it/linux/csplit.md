# csplit

> Divide un file in parti.
> Genera file denominati `xx00`, `xx01` e così via.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/csplit-invocation.html>.

- Divide un file in due parti, iniziando la seconda alla riga 10:

`csplit {{path/to/file}} 10`

- Divide un file in tre parti, iniziando le parti successive alle righe 7 e 23:

`csplit {{path/to/file}} 7 23`

- Inizia una nuova parte ogni 5 righe (fallisce se il numero di righe non è divisibile per 5):

`csplit {{path/to/file}} 5 {*}`

- Inizia una nuova parte ogni 5 righe, ignorando l'errore di divisione esatta:

`csplit {{[-k|--keep-files]}} {{path/to/file}} 5 {*}`

- Divide un file a partire dalla riga 5 e utilizza un prefisso personalizzato per i file di output (il prefisso predefinito è `xx`):

`csplit {{path/to/file}} 5 {{[-f|--prefix]}} {{prefix}}`

- Divide un file a partire dalla prima riga che corrisponde a un pattern `regex`:

`csplit {{path/to/file}} /{{regex}}/`
