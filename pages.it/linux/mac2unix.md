# mac2unix

> Cambia i terminazioni di riga in stile macOS in stile Unix.
> Sostituisce CR con LF.
> Vedi anche: `unix2dos`, `unix2mac`, `dos2unix`.
> Maggiori informazioni: <https://manned.org/mac2unix>.

- Cambia i terminazioni di riga di un file:

`mac2unix {{path/to/file}}`

- Crea una copia con terminazioni di riga in stile Unix:

`mac2unix {{[-n|--newfile]}} {{path/to/file}} {{path/to/new_file}}`

- Mostra informazioni sul file:

`mac2unix {{[-i|--info]}} {{path/to/file}}`

- Mantieni/aggiungi/rimuovi il BOM (Byte Order Mark):

`mac2unix --{{keep-bom|add-bom|remove-bom}} {{path/to/file}}`
