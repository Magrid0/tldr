# e2image

> Salva i metadati critici del filesystem ext2/ext3/ext4 in un file.
> Maggiori informazioni: <https://manned.org/e2image>.

- Scrive i metadati situati sul dispositivo in un file specifico:

`e2image {{/dev/sdXN}} {{path/to/file_immagine}}`

- Stampa i metadati situati sul dispositivo su `stdout`:

`e2image {{/dev/sdXN}} -`

- Ripristina i metadati del filesystem sul dispositivo:

`e2image -I {{/dev/sdXN}} {{path/to/file_immagine}}`

- Crea un file immagine [r]aw sparso di grandi dimensioni con metadati agli offset corretti:

`e2image -r {{/dev/sdXN}} {{path/to/file_immagine}}`

- Crea un file immagine [Q]COW2 invece di un file immagine normale o raw:

`e2image -Q {{/dev/sdXN}} {{path/to/file_immagine}}`
