# eyeD3

> Legge e manipola i metadati di file MP3.
> Maggiori informazioni: <https://manned.org/eyeD3>.

- Mostra le informazioni su un file MP3:

`eyeD3 {{filename.mp3}}`

- Imposta il titolo di un file MP3:

`eyeD3 {{[-t|--title]}} "{{Un Titolo}}" {{filename.mp3}}`

- Imposta l'album di tutti i file MP3 in una directory:

`eyeD3 {{[-A|--album]}} "{{Nome Album}}" {{*.mp3}}`

- Imposta l'immagine di copertina per un file MP3:

`eyeD3 --add-image {{front_cover.jpeg}}:FRONT_COVER: {{filename.mp3}}`
