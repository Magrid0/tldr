# dpigs

> Mostra quali pacchetti installati occupano più spazio su sistemi basati su `apt`.
> Maggiori informazioni: <https://manned.org/dpigs>.

- Mostra gli `n` pacchetti più grandi sul sistema:

`dpigs {{[-n|--lines]}} {{n}}`

- Usa il file specificato invece del file di stato dpkg predefinito:

`dpigs {{[-s|--status]}} {{path/to/file}}`

- Mostra i pacchetti sorgente più grandi dei pacchetti binari installati sul sistema:

`dpigs {{[-S|--source]}}`

- Mostra le dimensioni dei pacchetti in formato leggibile:

`dpigs {{[-H|--human-readable]}}`

- Mostra aiuto:

`dpigs {{[-h|--help]}}`
