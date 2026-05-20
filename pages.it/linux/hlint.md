# hlint

> Suggerisce miglioramenti al codice Haskell.
> Maggiori informazioni: <https://hackage.haskell.org/package/hlint>.

- Mostra suggerimenti per un dato file:

`hlint {{path/to/file}} options`

- Controlla tutti i file Haskell e genera un rapporto:

`hlint {{path/to/directory}} {{[-r|--report]}}`

- Applica automaticamente la maggior parte dei suggerimenti:

`hlint {{path/to/file}} --refactor`

- Mostra opzioni aggiuntive:

`hlint {{path/to/file}} --refactor-options`

- Genera un file di impostazioni ignorando tutti i suggerimenti in sospeso:

`hlint {{path/to/file}} --default > {{.hlint.yaml}}`
