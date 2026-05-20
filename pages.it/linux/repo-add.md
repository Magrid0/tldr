# repo-add

> Utilità di manutenzione del database dei pacchetti che permette l'installazione del pacchetto tramite Pacman.
> Vedi anche: `repo-remove`.
> Maggiori informazioni: <https://manned.org/repo-add>.

- Crea un repository vuoto:

`repo-add {{path/to/database.db.tar.gz}}`

- Aggiunge pacchetti al repository:

`repo-add {{path/to/database.db.tar.gz}} {{package1.pkg.tar.zst package2.pkg.tar.zst ...}}`

- Aggiunge tutti i binari dei pacchetti nella directory corrente e rimuove eventuali file di pacchetti obsoleti:

`repo-add {{[-R|--remove]}} {{path/to/database.db.tar.gz}} {{*.pkg.tar.zst}}`

- Aggiunge tutti i binari dei pacchetti nella directory corrente in modalità silenziosa tranne messaggi di avviso ed errore:

`repo-add {{[-q|--quiet]}} {{path/to/database.db.tar.gz}} {{*.pkg.tar.zst}}`

- Aggiunge tutti i binari dei pacchetti nella directory corrente senza mostrare colori:

`repo-add --nocolor {{path/to/database.db.tar.gz}} {{*.pkg.tar.zst}}`
