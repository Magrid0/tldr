# trash

> Gestisci il cestino.
> Maggiori informazioni: <https://github.com/andreafrancia/trash-cli>.

- Invia un file al cestino:

`trash {{percorso/del/file}}`

- Elenca tutti i file nel cestino:

`trash-list`

- Ripristina interattivamente un file dal cestino:

`trash-restore`

- Svuota il cestino:

`trash-empty`

- Elimina permanentemente tutti i file nel cestino più vecchi di 10 giorni:

`trash-empty 10`

- Rimuovi tutti i file nel cestino che corrispondono a un pattern blob specifico:

`trash-rm "{{*.o}}"`

- Rimuovi tutti i file con una posizione originale specifica:

`trash-rm /{{percorso/del/file_o_directory}}`
