# update-initramfs

> Gestisci initramfs.
> Maggiori informazioni: <https://manned.org/update-initramfs>.

- Crea un nuovo initramfs (usa `all` per tutte le versioni del kernel installate):

`sudo update-initramfs -c -k {{versione_kernel}}`

- Aggiorna un initramfs esistente:

`sudo update-initramfs -u`

- Rimuovi un initramfs esistente (usa cautela quando usi `all` per `versione_kernel`):

`sudo update-initramfs -d -k {{versione_kernel}}`
