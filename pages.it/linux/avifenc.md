# avifenc

> Codificatore AV1 Image File Format (AVIF).
> Maggiori informazioni: <https://aomediacodec.github.io/av1-avif/>.

- Converte un'immagine PNG specifica in AVIF:

`avifenc {{path/to/input.png}} {{path/to/output.avif}}`

- Codifica con una velocità specifica (6=predefinita, 0=più lenta, 10=più veloce):

`avifenc --speed {{2}} {{path/to/input.png}} {{path/to/output.avif}}`
