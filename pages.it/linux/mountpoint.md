# mountpoint

> Verifica se una directory è un punto di montaggio del filesystem.
> Maggiori informazioni: <https://manned.org/mountpoint>.

- Controlla se una directory è un punto di montaggio:

`mountpoint {{path/to/directory}}`

- Controlla se una directory è un punto di montaggio senza mostrare alcun output:

`mountpoint {{[-q|--quiet]}} {{path/to/directory}}`

- Mostra i numeri major/minor del filesystem di un punto di montaggio:

`mountpoint {{[-d|--fs-devno]}} {{path/to/directory}}`
