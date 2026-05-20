# fadvise

> Controlla il comportamento di caching dei file Linux.
> Vedi anche: `fincore`.
> Maggiori informazioni: <https://manned.org/fadvise>.

- Precariica un file o una directory nella cache:

`fadvise {{[-a|--advice]}} willneeded {{path/to/file_or_directory}}`

- Suggerisce di rimuovere un file dalla cache:

`fadvise {{path/to/file}}`

- Mostra aiuto:

`fadvise {{[-h|--help]}}`
