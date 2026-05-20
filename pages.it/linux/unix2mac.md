# unix2mac

> Cambia le terminazioni di riga in stile Unix in stile macOS.
> Sostituisce LF con CR.
> Vedi anche: `unix2dos`, `dos2unix`, `mac2unix`.
> Maggiori informazioni: <https://manned.org/unix2mac>.

- Cambia le terminazioni di riga di un file:

`unix2mac {{percorso/del/file}}`

- Crea una copia con terminazioni di riga in stile macOS:

`unix2mac {{[-n|--newfile]}} {{percorso/del/file}} {{percorso/del/nuovo_file}}`

- Mostra informazioni sul file:

`unix2mac {{[-i|--info]}} {{percorso/del/file}}`

- Mantieni/aggiungi/rimuovi il Byte Order Mark:

`unix2mac --{{keep-bom|add-bom|remove-bom}} {{percorso/del/file}}`
