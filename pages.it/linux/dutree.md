# dutree

> Analizza l'utilizzo del filesystem con alberi testuali colorati.
> Maggiori informazioni: <https://github.com/nachoparker/dutree#usage>.

- Mostra un albero grafico della directory corrente:

`dutree`

- Mostra una directory specifica:

`dutree {{path/to/directory}}`

- Aggrega elementi più piccoli di un numero di KB (o M per MB, o G per GB):

`dutree --aggr {{number}}K`

- Mostra le sottodirectory fino alla profondità specificata (default è 1):

`dutree --depth {{depth}}`

- Salta le directory per una rapida panoramica locale:

`dutree --files-only`

- Esclude i file nascosti:

`dutree --no-hidden`
