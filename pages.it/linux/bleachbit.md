# bleachbit

> Pulisce file spazzatura dal filesystem.
> Maggiori informazioni: <https://docs.bleachbit.org/doc/command-line-interface.html>.

- Avvia la versione con interfaccia grafica (GUI) di Bleachbit:

`bleachbit --gui`

- Distrugge un file:

`bleachbit {{[-s|--shred]}} {{path/to/file}}`

- Elenca le opzioni di pulizia disponibili:

`bleachbit {{[-l|--list-cleaners]}}`

- Anteprima dei file che verranno eliminati e delle altre modifiche che verranno apportate prima di eseguire effettivamente l'operazione di pulizia:

`bleachbit {{[-p|--preview]}} --preset {{cleaner1.option1 cleaner2.option2 ...}}`

- Esegue l'operazione di pulizia ed elimina i file:

`bleachbit {{[-c|--clean]}} --preset {{cleaner1.option1 cleaner2.option2 ...}}`
