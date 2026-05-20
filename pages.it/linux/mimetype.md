# mimetype

> Determina automaticamente il tipo MIME di un file.
> Maggiori informazioni: <https://manned.org/mimetype>.

- Stampa il tipo MIME di un dato file:

`mimetype {{path/to/file}}`

- Mostra solo il tipo MIME, e non il nome del file:

`mimetype --brief {{path/to/file}}`

- Mostra una descrizione del tipo MIME:

`mimetype --describe {{path/to/file}}`

- Determina il tipo MIME di `stdin` (non controlla un nome file):

`{{command}} | mimetype --stdin`

- Mostra informazioni di debug su come è stato determinato il tipo MIME:

`mimetype --debug {{path/to/file}}`

- Mostra tutti i possibili tipi MIME di un dato file in ordine di confidenza:

`mimetype --all {{path/to/file}}`

- Specifica esplicitamente il codice lingua a 2 lettere dell'output:

`mimetype --language {{path/to/file}}`
