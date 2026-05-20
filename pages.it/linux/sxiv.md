# sxiv

> Simple X Image Viewer.
> Maggiori informazioni: <https://manned.org/sxiv>.

- Apre un'immagine:

`sxiv {{percorso/dell/immagine}}`

- Apre un'immagine in modalità schermo intero:

`sxiv -f {{percorso/del/file}}`

- Apre un elenco di immagini separato da nuove righe, leggendo i nomi dei file da `stdin`:

`echo {{percorso/del/file}} | sxiv -i`

- Apre una o più immagini come presentazione:

`sxiv -S {{secondi}} {{percorso/dell/immagine1 percorso/dell/immagine2 ...}}`

- Apre una o più immagini in modalità miniature:

`sxiv -t {{percorso/dell/immagine1 percorso/dell/immagine2 ...}}`
