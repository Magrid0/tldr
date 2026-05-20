# mkisofs

> Crea file ISO da directory.
> Anche alias di `genisoimage`.
> Maggiori informazioni: <https://manned.org/mkisofs>.

- Crea un ISO da una directory:

`mkisofs -o {{filename.iso}} {{path/to/source_directory}}`

- Imposta l'etichetta del disco durante la creazione di un ISO:

`mkisofs -o {{filename.iso}} -V "{{label_name}}" {{path/to/source_directory}}`

- Crea un'immagine ISO con file più grandi di 2 GiB segnalando una dimensione apparente più piccola per filesystem ISO9660:

`mkisofs -o {{filename.iso}} -allow-limited-size {{path/to/source_directory}}`
