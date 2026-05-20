# lsinitrd

> Mostra il contenuto di un'immagine initramfs.
> Vedi anche: `dracut`.
> Maggiori informazioni: <https://github.com/dracutdevs/dracut/blob/master/man/lsinitrd.1.asc>.

- Mostra il contenuto dell'immagine initramfs per il kernel corrente:

`lsinitrd`

- Mostra il contenuto dell'immagine initramfs per il kernel specificato:

`lsinitrd {{[-k|--kver]}} {{kernel_version}}`

- Mostra il contenuto dell'immagine initramfs specificata:

`lsinitrd {{path/to/initramfs.img}}`

- Elenca i moduli inclusi nell'immagine initramfs:

`lsinitrd {{[-m|--mod]}}`

- Estrae l'initramfs nella directory corrente:

`lsinitrd --unpack`
