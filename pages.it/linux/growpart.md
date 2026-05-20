# growpart

> Estende una partizione in un disco o immagine disco per riempire lo spazio disponibile.
> Maggiori informazioni: <https://github.com/canonical/cloud-utils>.

- Estende la partizione `n` da `sdX` per riempire lo spazio vuoto fino alla fine del disco o all'inizio della partizione successiva:

`growpart {{/dev/sdX}} {{n}}`

- Mostra quali modifiche verrebbero apportate durante l'estensione della partizione `n` in un'immagine disco:

`growpart {{[-N|--dry-run]}} /{{path/to/disk.img}} {{n}}`
