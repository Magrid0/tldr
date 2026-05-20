# unix2dos

> Cambia le terminazioni di riga in stile Unix in stile DOS.
> Sostituisce LF con CRLF.
> Vedi anche: `unix2mac`, `dos2unix`, `mac2unix`.
> Maggiori informazioni: <https://manned.org/unix2dos>.

- Cambia le terminazioni di riga di un file:

`unix2dos {{percorso/del/file}}`

- Crea una copia con terminazioni di riga in stile DOS:

`unix2dos {{[-n|--newfile]}} {{percorso/del/file}} {{percorso/del/nuovo_file}}`

- Mostra informazioni sul file:

`unix2dos {{[-i|--info]}} {{percorso/del/file}}`

- Mantieni/aggiungi/rimuovi il Byte Order Mark:

`unix2dos --{{keep-bom|add-bom|remove-bom}} {{percorso/del/file}}`
