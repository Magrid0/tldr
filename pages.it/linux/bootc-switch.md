# bootc switch

> Punta a un nuovo riferimento di immagine contenitore per l'avvio.
> Maggiori informazioni: <https://manned.org/bootc-switch>.

- Cambia il sistema operativo base con una nuova immagine contenitore da un registro:

`sudo bootc switch {{image}}`

- Cambia il sistema operativo base con una nuova immagine contenitore dall'archivio immagini locale dell'utente root:

`sudo bootc switch --transport containers-storage {{image}}`

- Cambia il sistema operativo base con una nuova immagine contenitore archiviata in un tarball:

`sudo bootc switch --transport oci-archive {{path/to/image.tar.gz}}`
