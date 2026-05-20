# mksquashfs

> Crea o aggiunge file e directory a filesystem squashfs.
> Maggiori informazioni: <https://manned.org/mksquashfs>.

- Crea o aggiunge file e directory a un filesystem squashfs (compresso usando `gzip` per impostazione predefinita):

`mksquashfs {{path/to/file_or_directory1 path/to/file_or_directory2 ...}} {{filesystem.squashfs}}`

- Crea o aggiunge file e directory a un filesystem squashfs, usando un algoritmo di [comp]ressione specifico:

`mksquashfs {{path/to/file_or_directory1 path/to/file_or_directory2 ...}} {{filesystem.squashfs}} -comp {{gzip|lzo|lz4|xz|zstd|lzma}}`

- Crea o aggiunge file e directory a un filesystem squashfs, [e]scludendone alcuni:

`mksquashfs {{path/to/file_or_directory1 path/to/file_or_directory2 ...}} {{filesystem.squashfs}} -e {{file|directory1 file|directory2 ...}}`

- Crea o aggiunge file e directory a un filesystem squashfs, [e]scludendo quelli che terminano con gzip:

`mksquashfs {{path/to/file_or_directory1 path/to/file_or_directory2 ...}} {{filesystem.squashfs}} -wildcards -e "{{*.gz}}"`

- Crea o aggiunge file e directory a un filesystem squashfs, [e]scludendo quelli corrispondenti a un `regex`:

`mksquashfs {{path/to/file_or_directory1 path/to/file_or_directory2 ...}} {{filesystem.squashfs}} -regex -e "{{regex}}"`
