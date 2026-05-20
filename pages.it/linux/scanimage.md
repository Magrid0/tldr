# scanimage

> Acquisisce immagini con l'API Scanner Access Now Easy.
> Maggiori informazioni: <http://sane-project.org/man/scanimage.1.html>.

- Elenca gli scanner disponibili per assicurarsi che il dispositivo di destinazione sia connesso e riconosciuto:

`scanimage {{[-L|--list-devices]}}`

- Acquisisce un'immagine e la salva in un file:

`scanimage --format {{pnm|tiff|png|jpeg|pdf|...}} > {{percorso/della/nuova_immagine}}`

- Specifica il dispositivo da cui acquisire:

`scanimage {{[-d|--device]}} {{nome_dispositivo}} > {{percorso/della/nuova_immagine}}`

- Specifica la risoluzione per l'immagine acquisita (la risoluzione predefinita è 75dpi):

`scanimage --resolution {{300}} > {{percorso/della/nuova_immagine}}`
