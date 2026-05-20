# zsync

> Scaricatore di file parziale/differenziale.
> HTTPS non è supportato - usa solo URL HTTP.
> Vedi anche: `rsync`.
> Maggiori informazioni: <https://manned.org/zsync>.

- Scarica un file usando un file di controllo `.zsync`:

`zsync {{path/to/url.zsync}}`

- Usa un file locale come seed per evitare di scaricare nuovamente parti invariate:

`zsync -i {{path/to/file_esistente}} {{path/to/url.zsync}}`

- Salva il file aggiornato con un nome specifico:

`zsync -i {{path/to/file_esistente}} -o {{path/to/nuovo_file}} {{path/to/url.zsync}}`

- Riprendi un download parziale e mantieni il file temporaneo:

`zsync -k {{path/to/url.zsync}}`

- Esegui in modalità silenziosa con output minimo (nessuna barra di progresso, velocità di download o stima del tempo rimanente):

`zsync -q {{path/to/url.zsync}}`
