# gphoto2

> Controlla fotocamere digitali dalla riga di comando.
> Maggiori informazioni: <http://www.gphoto.org/doc/manual/ref-gphoto2-cli.html>.

- Elenca le fotocamere collegate:

`gphoto2 --auto-detect`

- Elenca i file sulla fotocamera:

`gphoto2 {{[-L|--list-files]}}`

- Scarica tutte le immagini:

`gphoto2 {{[-P|--get-all-files]}}`

- Scarica solo le immagini nuove (salta le esistenti):

`gphoto2 {{[-P|--get-all-files]}} --new`

- Scarica i file da 1 a 5:

`gphoto2 {{[-p|--get-file]}} 1-5`

- Elimina tutti i file sulla fotocamera:

`gphoto2 {{[-D|--delete-all-files]}}`

- Cattura un'immagine e la scarica:

`gphoto2 --capture-image-and-download`

- Mostra le informazioni della fotocamera:

`gphoto2 --summary`
