# partx

> Analizza una tabella delle partizioni e la comunica al kernel.
> Maggiori informazioni: <https://manned.org/partx>.

- Elenca le partizioni su un dispositivo a blocchi o un'immagine disco:

`sudo partx {{[-l|--list]}} {{percorso/del/dispositivo_o_immagine_disco}}`

- Aggiunge tutte le partizioni trovate in un dato dispositivo a blocchi al kernel:

`sudo partx {{[-a|--add]}} {{[-v|--verbose]}} {{percorso/del/dispositivo_o_immagine_disco}}`

- Elimina tutte le partizioni trovate dal kernel (non altera le partizioni sul disco):

`sudo partx {{[-d|--delete]}} {{percorso/del/dispositivo_o_immagine_disco}}`
