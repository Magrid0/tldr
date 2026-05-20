# dos2unix

> Converte terminazioni di riga in stile DOS in stile Unix.
> Sostituisce CRLF con LF.
> Vedi anche: `unix2dos`, `unix2mac`, `mac2unix`.
> Maggiori informazioni: <https://manned.org/dos2unix>.

- Modifica le terminazioni di riga di un file:

`dos2unix {{path/to/file}}`

- Crea una copia con terminazioni di riga in stile Unix:

`dos2unix {{[-n|--newfile]}} {{path/to/file}} {{path/to/new_file}}`

- Mostra le informazioni del file:

`dos2unix {{[-i|--info]}} {{path/to/file}}`

- Mantiene/aggiunge/rimuove il Byte Order Mark:

`dos2unix --{{keep-bom|add-bom|remove-bom}} {{path/to/file}}`
