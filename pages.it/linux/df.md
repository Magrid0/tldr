# df

> Mostra una panoramica dell'utilizzo dello spazio disco del filesystem.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/df-invocation.html>.

- Mostra tutti i filesystem e il loro utilizzo disco:

`df`

- Mostra tutti i filesystem in formato leggibile:

`df {{[-h|--human-readable]}}`

- Mostra il filesystem contenente il file o la directory specificati:

`df {{path/to/file_or_directory}}`

- Include statistiche sul numero di inode liberi:

`df {{[-i|--inodes]}}`

- Mostra i filesystem escludendo i tipi specificati:

`df {{[-x|--exclude-type]}} {{squashfs}} {{[-x|--exclude-type]}} {{tmpfs}}`

- Mostra i tipi di filesystem:

`df {{[-T|--print-type]}}`
