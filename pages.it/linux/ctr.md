# ctr

> Gestisce container e immagini di `containerd`.
> Maggiori informazioni: <https://manned.org/ctr>.

- Elenca tutti i container (in esecuzione e arrestati):

`ctr containers list`

- Elenca tutte le immagini:

`ctr images list`

- Scarica un'immagine:

`ctr images pull {{image}}`

- Assegna un tag a un'immagine:

`ctr images tag {{source_image}}:{{source_tag}} {{target_image}}:{{target_tag}}`
