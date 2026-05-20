# xmount

> Converte al volo tra molteplici tipi di immagini di dischi rigidi di input e output con supporto opzionale di write cache.
> Crea un filesystem virtuale usando FUSE (Filesystem in Userspace) che contiene una rappresentazione virtuale dell'immagine di input.
> Maggiori informazioni: <https://manned.org/xmount>.

- Monta un file immagine `.raw` in un file contenitore DMG:

`xmount --in {{raw}} {{path/to/image.dd}} --out {{dmg}} {{punto_di_mount}}`

- Monta un file immagine EWF con supporto write-cache in un file VHD per l'avvio:

`xmount --cache {{path/to/cache.ovl}} --in {{ewf}} {{path/to/image.E??}} --out {{vhd}} {{punto_di_mount}}`

- Monta la prima partizione al settore 2048 in un nuovo file immagine `.raw`:

`xmount --offset {{2048}} --in {{raw}} {{path/to/image.dd}} --out {{raw}} {{punto_di_mount}}`
