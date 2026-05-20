# setfattr

> Imposta attributi estesi dei file.
> Maggiori informazioni: <https://manned.org/setfattr>.

- Imposta il nome di un attributo per un file:

`setfattr {{[-n|--name]}} user.{{nome_attributo}} {{percorso/del/file}}`

- Imposta un valore definito dall'utente di un attributo esteso su un file:

`setfattr {{[-n|--name]}} user.{{nome_attributo}} {{[-v|--value]}} "{{valore}}" {{percorso/del/file}}`

- Rimuove un attributo specifico da un file:

`setfattr {{[-x|--remove]}} user.{{nome_attributo}} {{percorso/del/file}}`
