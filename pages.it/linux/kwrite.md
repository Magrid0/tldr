# kwrite

> Editor di testo del progetto KDE Desktop.
> Vedi anche: `kate`.
> Maggiori informazioni: <https://docs.kde.org/stable_kf6/en/kate/kwrite/command-line-options.html>.

- Apre un file di testo:

`kwrite {{path/to/file}}`

- Apre più file di testo:

`kwrite {{file1 file2 ...}}`

- Apre un file di testo con una codifica specifica:

`kwrite --encoding {{UTF-8}} {{path/to/file}}`

- Apre un file di testo e naviga a una riga e colonna specifica:

`kwrite --line {{line_number}} --column {{column_number}} {{path/to/file}}`
