# beet

> Gestisce la libreria multimediale beets.
> Maggiori informazioni: <https://beets.readthedocs.io/en/stable/reference/cli.html>.

- Aggiunge musica da una directory specifica alla libreria, tentando di ottenere i tag corretti da MusicBrainz:

`beet import {{path/to/directory}}`

- Aggiunge un singolo brano alla libreria, tentando di ottenere i tag corretti da MusicBrainz:

`beet import {{[-s|--singletons]}} {{path/to/file}}`

- Interroga la libreria:

`beet list {{query}}`

- Mostra le statistiche complete della libreria:

`beet stats`

- Mostra le statistiche per una query specifica:

`beet stats {{query}}`
