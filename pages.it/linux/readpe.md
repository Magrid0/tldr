# readpe

> Mostra informazioni sui file PE.
> Maggiori informazioni: <https://manned.org/readpe>.

- Mostra tutte le informazioni su un file PE:

`readpe {{path/to/executable}}`

- Mostra tutti gli header presenti in un file PE:

`readpe --all-headers {{path/to/executable}}`

- Mostra tutte le sezioni presenti in un file PE:

`readpe --all-sections {{path/to/executable}}`

- Mostra un header specifico da un file PE:

`readpe --header {{dos|coff|optional}} {{path/to/executable}}`

- Elenca tutte le funzioni importate:

`readpe --imports {{path/to/executable}}`

- Elenca tutte le funzioni esportate:

`readpe --exports {{path/to/executable}}`
