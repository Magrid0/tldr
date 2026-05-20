# eu-readelf

> Mostra informazioni sui file ELF.
> Maggiori informazioni: <https://manned.org/eu-readelf>.

- Mostra tutte le informazioni estraibili contenute nel file ELF:

`eu-readelf {{[-a|--all]}} {{path/to/file}}`

- Mostra il contenuto di tutti i segmenti/sezioni NOTE, o di un particolare segmento/sezione:

`eu-readelf {{[-n|--notes]}} {{.note.ABI-tag}} {{path/to/file}}`
