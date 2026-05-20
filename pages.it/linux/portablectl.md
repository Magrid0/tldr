# portablectl

> Utilità systemd per gestire e distribuire immagini di servizi portatili su sistemi Linux.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/portablectl.html>.

- Elenca le immagini di servizi portatili disponibili trovate nei percorsi di ricerca:

`portablectl list`

- Collega un'immagine di servizio portatile al sistema host:

`portablectl attach {{percorso/all/immagine}}`

- Scollega un'immagine di servizio portatile dal sistema host:

`portablectl detach {{percorso/all/immagine|nome_immagine}}`

- Mostra dettagli e metadati di un'immagine di servizio portatile specificata:

`portablectl inspect {{percorso/all/immagine}}`

- Controlla se un'immagine di servizio portatile è collegata al sistema host:

`portablectl is-attached {{percorso/all/immagine|nome_immagine}}`
