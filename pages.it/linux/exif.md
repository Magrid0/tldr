# exif

> Mostra e modifica le informazioni EXIF nei file JPEG.
> Maggiori informazioni: <https://manned.org/exif>.

- Mostra tutte le informazioni EXIF riconosciute in un'immagine:

`exif {{path/to/immagine.jpg}}`

- Mostra una tabella con i tag EXIF noti e se ciascuno esiste in un'immagine:

`exif {{[-l|--list-tags]}} --no-fixup {{path/to/immagine.jpg}}`

- Estrae la miniatura dell'immagine in un file separato:

`exif {{[-e|--extract-thumbnail]}} {{[-o|--output]}} {{path/to/miniatura.jpg}} {{path/to/immagine.jpg}}`

- Mostra il contenuto grezzo del tag "Model" nell'immagine data:

`exif --ifd {{0}} {{[-t|--tag]}} "Model" {{[-m|--machine-readable]}} {{path/to/immagine.jpg}}`

- Cambia il valore del tag "Artist" in John Smith e salva in `new.jpg`:

`exif {{[-o|--output]}} {{path/to/new.jpg}} --ifd {{0}} {{[-t|--tag]}} "Artist" --set-value "John Smith" --no-fixup {{path/to/immagine.jpg}}`
