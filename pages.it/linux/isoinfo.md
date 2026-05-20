# isoinfo

> Programmi di utilità per scaricare e verificare immagini disco ISO.
> Maggiori informazioni: <https://manned.org/isoinfo>.

- Elenca tutti i file inclusi in un'immagine ISO:

`isoinfo -f -i {{path/to/image.iso}}`

- Estrae un file specifico da un'immagine ISO e lo invia su `stdout`:

`isoinfo -i {{path/to/image.iso}} -x {{/PATH/TO/FILE/INSIDE/ISO.EXT}}`

- Mostra le informazioni di intestazione per un'immagine disco ISO:

`isoinfo -d -i {{path/to/image.iso}}`
