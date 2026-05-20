# mkid

> Costruisce un database ID per l'uso con `lid` e altri strumenti idutils.
> Maggiori informazioni: <https://www.gnu.org/software/idutils/manual/idutils.html#mkid-invocation>.

- Costruisce un database ID per la directory corrente:

`mkid`

- Costruisce un database ID per directory specifiche:

`mkid {{path/to/directory1 path/to/directory2 ...}}`

- Costruisce un database ID e lo salva in un file specifico:

`mkid {{[-o|--output]}} {{path/to/database.id}}`

- Include solo linguaggi specifici:

`mkid {{[-i|--include]}} "{{language1 language2 ...}}"`

- Esclude directory specifiche dall'indicizzazione:

`mkid {{[-p|--prune]}} {{path/to/excluded_directory}}`

- Mostra statistiche dopo aver costruito il database:

`mkid {{[-s|--statistics]}}`
