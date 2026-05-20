# mkinitfs

> Genera un initramfs su Alpine Linux.
> Maggiori informazioni: <https://manned.org/mkinitfs>.

- Genera un initramfs con le funzionalità specificate in `/etc/mkinitfs/mkinitfs.conf`:

`mkinitfs`

- Usa un file di configurazione diverso:

`mkinitfs -c {{path/to/config}}`

- Comprimi l'initramfs usando l'algoritmo di compressione specificato (predefinito: gzip):

`mkinitfs -C {{gzip|xz|zstd|lz4|none}}`

- Elenca i file che saranno inclusi nell'immagine initramfs:

`mkinitfs -l`

- Elenca tutte le funzionalità disponibili:

`mkinitfs -L`
