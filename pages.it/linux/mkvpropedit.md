# mkvpropedit

> Modifica le proprietà di file Matroska esistenti senza un completo remux.
> Maggiori informazioni: <https://mkvtoolnix.download/doc/mkvpropedit.html>.

- Elimina il titolo:

`mkvpropedit {{[-d|--delete]}} title {{path/to/file.mkv}}`

- Segna la traccia sottotitoli 3 come SDH - Sottotitoli per non udenti e ipoudenti:

`mkvpropedit {{path/to/file.mkv}} {{[-e|--edit]}} track:s3 {{[-s|--set]}} flag-hearing-impaired=1`

- Segna la traccia audio 2 come Predefinita:

`mkvpropedit {{path/to/file.mkv}} {{[-e|--edit]}} track:a2 {{[-s|--set]}} flag-default=1`

- Elimina il nome della traccia video 1:

`mkvpropedit {{path/to/file.mkv}} {{[-e|--edit]}} track:v1 {{[-d|--delete]}} name`
