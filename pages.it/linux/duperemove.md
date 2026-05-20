# duperemove

> Trova extent duplicati del filesystem e opzionalmente li pianifica per la deduplicazione.
> Un extent è una piccola parte di un file all'interno del filesystem.
> Su alcuni filesystem un extent può essere referenziato più volte, quando parti del contenuto dei file sono identiche.
> Maggiori informazioni: <https://markfasheh.github.io/duperemove/>.

- Cerca extent duplicati in una directory e li mostra:

`duperemove -r {{path/to/directory}}`

- Deduplica extent duplicati su un filesystem Btrfs o XFS (sperimentale):

`duperemove -r -d {{path/to/directory}}`

- Usa un file di hash per memorizzare gli hash degli extent (meno uso di memoria e può essere riutilizzato nelle esecuzioni successive):

`duperemove -r -d --hashfile={{path/to/hashfile}} {{path/to/directory}}`

- Limita i thread I/O (per la fase di hashing e deduplica) e i thread CPU (per la fase di ricerca extent duplicati):

`duperemove -r -d --hashfile={{path/to/hashfile}} --io-threads={{n}} --cpu-threads={{n}} {{path/to/directory}}`
