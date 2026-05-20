# pdfattach

> Aggiunge un nuovo allegato (file incorporato) a un file PDF esistente.
> Vedi anche: `pdfdetach`, `pdfimages`, `pdfinfo`.
> Maggiori informazioni: <https://manned.org/pdfattach>.

- Aggiungi un nuovo allegato a un file PDF esistente:

`pdfattach {{percorso/input.pdf}} {{percorso/file_da_allegare}} {{percorso/output.pdf}}`

- Sostituisce l'allegato con lo stesso nome se esiste:

`pdfattach -replace {{percorso/input.pdf}} {{percorso/file_da_allegare}} {{percorso/output.pdf}}`

- Mostra aiuto:

`pdfattach {{[-h|--help]}}`

- Mostra versione:

`pdfattach -v`
