# bchunk

> Converte immagini CD in un insieme di tracce `.iso` e `.cdr`.
> Maggiori informazioni: <https://manned.org/bchunk>.

- Converte un CD binario in un file immagine iso9960 standard:

`bchunk {{path/to/image.bin}} {{path/to/image.cue}} {{path/to/output}}`

- Converte con modalità verbosa:

`bchunk -v {{path/to/image.bin}} {{path/to/image.cue}} {{path/to/output}}`

- Produce file audio in formato WAV:

`bchunk -w {{path/to/image.bin}} {{path/to/image.cue}} {{path/to/output}}`
