# head

> Stampa a schermo le prime linee di file.
> Vedi anche: `tail`.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/head-invocation.html>.

- Mostra le prime 10 linee di un file:

`head {{path/to/file}}`

- Mostra le prime 10 linee di più file:

`head {{path/to/file1 path/to/file2 ...}}`

- Mostra le prime 5 linee di un file:

`head {{[-5|--lines 5]}} {{path/to/file}}`

- Mostra le prime linee di un file:

`head {{[-n|--lines]}} {{count}} {{path/to/file}}`

- Mostra i primi byte di un file:

`head {{[-c|--bytes]}} {{count}} {{path/to/file}}`

- Mostra tutto il file tranne le ultime linee:

`head {{[-n|--lines]}} -{{count}} {{path/to/file}}`

- Mostra tutto il file tranne gli ultimi byte:

`head {{[-c|--bytes]}} -{{count}} {{path/to/file}}`
