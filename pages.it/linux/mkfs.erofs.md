# mkfs.erofs

> Crea un filesystem EROFS in un'immagine.
> Maggiori informazioni: <https://manned.org/mkfs.erofs>.

- Crea un filesystem EROFS basato sulla directory radice:

`mkfs.erofs image.erofs root/`

- Crea un'immagine EROFS con un UUID specifico:

`mkfs.erofs -U {{UUID}} image.erofs root/`

- Crea un'immagine EROFS compressa:

`mkfs.erofs -zlz4hc image.erofs root/`

- Crea un'immagine EROFS in cui tutti i file sono di proprietà di root:

`mkfs.erofs --all-root image.erofs root/`
