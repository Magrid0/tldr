# run-mailcap

> Esegue programmi tramite voci nel file mailcap.
> Maggiori informazioni: <https://manned.org/run-mailcap>.

- Compone qualsiasi file esistente o nuovo con lo strumento di modifica `mailcap` predefinito:

`run-mailcap --action=compose {{path/to/file}}`

- Visualizza qualsiasi file con l'esploratore `mailcap` predefinito:

`run-mailcap --action=edit {{path/to/file}}`

- Stampa un file usando lo strumento di stampa `mailcap` predefinito:

`run-mailcap --action=print {{path/to/file}}`

- Visualizza qualsiasi file (di solito immagine) con l'esploratore `mailcap` predefinito:

`run-mailcap --action=view {{path/to/file}}`

- Invoca azioni/programmi individuali su run-mailcap:

`run-mailcap --action={{view|cat|compose|composetyped|edit|print}} {{path/to/file}}`

- Attiva informazioni aggiuntive:

`run-mailcap --action={{action}} --debug {{path/to/file}}`

- Ignora qualsiasi direttiva "copiousoutput" e inoltra l'output a `stdout`:

`run-mailcap --action={{action}} --nopager {{path/to/file}}`

- Mostra il comando trovato senza eseguirlo effettivamente:

`run-mailcap --action={{action}} --norun {{path/to/file}}`
