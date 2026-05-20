# compsize

> Calcola il rapporto di compressione di un insieme di file su un filesystem btrfs.
> Vedi anche: `btrfs filesystem`.
> Maggiori informazioni: <https://manned.org/compsize>.

- Calcola il rapporto di compressione corrente per un file o una directory:

`sudo compsize {{path/to/file_or_directory}}`

- Non attraversa i confini del filesystem:

`sudo compsize {{[-x|--one-file-system]}} {{path/to/file_or_directory}}`

- Mostra i conteggi di byte grezzi invece delle dimensioni leggibili dall'uomo:

`sudo compsize {{[-b|--bytes]}} {{path/to/file_or_directory}}`
