# readelf

> Mostra informazioni sui file ELF.
> Maggiori informazioni: <https://manned.org/readelf>.

- Mostra tutte le informazioni sul file ELF:

`readelf -all {{path/to/binary}}`

- Mostra tutti gli header presenti nel file ELF:

`readelf --headers {{path/to/binary}}`

- Mostra le voci nella tabella dei simboli del file ELF, se presente:

`readelf --symbols {{path/to/binary}}`

- Mostra le informazioni dell'header ELF:

`readelf --file-header {{path/to/binary}}`

- Mostra le informazioni dell'header di sezione ELF:

`readelf --section-headers {{path/to/binary}}`
