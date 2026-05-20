# mate-search-tool

> Cerca file nell'ambiente desktop MATE.
> Maggiori informazioni: <https://manned.org/mate-search-tool>.

- Cerca file contenenti una stringa specifica nel nome in una directory specifica:

`mate-search-tool --named={{string}} --path={{path/to/directory}}`

- Cerca file senza attendere la conferma dell'utente:

`mate-search-tool --start --named={{string}} --path={{path/to/directory}}`

- Cerca file con nome corrispondente a un `regex` specifico:

`mate-search-tool --start --regex={{string}} --path={{path/to/directory}}`

- Imposta un ordinamento nei risultati di ricerca:

`mate-search-tool --start --named={{string}} --path={{path/to/directory}} --sortby={{name|folder|size|type|date}}`

- Imposta un ordinamento decrescente:

`mate-search-tool --start --named={{string}} --path={{path/to/directory}} --descending`

- Cerca file di proprietà di un utente/gruppo specifico:

`mate-search-tool --start --{{user|group}}={{value}} --path={{path/to/directory}}`
