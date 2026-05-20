# mktemp

> Crea un file o una directory temporanea.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/mktemp-invocation.html>.

- Crea un file temporaneo vuoto e stampa il suo percorso assoluto:

`mktemp`

- Usa una directory personalizzata (predefinita a `$TMPDIR`, o `/tmp`):

`mktemp {{[-p |--tmpdir=]}}/{{path/to/temporary_directory}}`

- Usa un modello di percorso personalizzato (le `X` vengono sostituite con caratteri alfanumerici casuali):

`mktemp {{/tmp/example.XXXXXXXX}}`

- Usa un modello di nome file personalizzato:

`mktemp -t {{example.XXXXXXXX}}`

- Crea un file temporaneo vuoto con il suffisso specificato e stampa il suo percorso assoluto:

`mktemp --suffix {{.ext}}`

- Crea una directory temporanea vuota e stampa il suo percorso assoluto:

`mktemp {{[-d|--directory]}}`

- Stampa il nome di un file o directory temporanea senza crearlo effettivamente:

`mktemp {{[-u|--dry-run]}}`
