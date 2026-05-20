# einfo

> Fornisce il numero di record indicizzati in ciascun campo del database, la data dell'ultimo aggiornamento del database e i collegamenti disponibili dal database ad altri database Entrez.
> Maggiori informazioni: <https://www.ncbi.nlm.nih.gov/books/NBK179288/>.

- Stampa tutti i nomi dei database:

`einfo -dbs`

- Stampa tutte le informazioni del database protein in formato XML:

`einfo -db {{protein}}`

- Stampa tutti i campi del database nuccore:

`einfo -db {{nuccore}} -fields`

- Stampa tutti i collegamenti del database protein:

`einfo -db {{protein}} -links`
