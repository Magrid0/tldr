# xsel

> Strumento di manipolazione della selezione e degli appunti X11.
> Maggiori informazioni: <https://manned.org/xsel>.

- Usa l'output di un comando come input degli appunti (equivalente a `<Ctrl c>`):

`echo 123 | xsel {{[-ib|--input --clipboard]}}`

- Usa il contenuto di un file come input degli appunti:

`cat {{path/to/file}} | xsel {{[-ib|--input --clipboard]}}`

- Output del contenuto degli appunti nel terminale (equivalente a `<Ctrl v>`):

`xsel {{[-ob|--output --clipboard]}}`

- Output del contenuto degli appunti in un file:

`xsel {{[-ob|--output --clipboard]}} > {{path/to/file}}`

- Cancella gli appunti:

`xsel {{[-cb|--clear --clipboard]}}`

- Output del contenuto della selezione primaria X11 nel terminale (equivalente a un `<MiddleClick>` del mouse):

`xsel {{[-op|--output --primary]}}`
