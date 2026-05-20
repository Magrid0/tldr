# pdfdetach

> Elenca o estrae allegati (file incorporati) da un file PDF.
> Vedi anche: `pdfattach`, `pdfimages`, `pdfinfo`.
> Maggiori informazioni: <https://manned.org/pdfdetach>.

- Elenca tutti gli allegati in un file con una codifica di testo specifica:

`pdfdetach list -enc {{UTF-8}} {{percorso/input.pdf}}`

- Salva un file incorporato specifico specificando il suo numero:

`pdfdetach -save {{numero}} {{percorso/input.pdf}}`

- Salva un file incorporato specifico specificando il suo nome:

`pdfdetach -savefile {{nome}} {{percorso/input.pdf}}`

- Salva il file incorporato con un nome file di output personalizzato:

`pdfdetach -save {{numero}} -o {{percorso/output}} {{percorso/input.pdf}}`

- Salva l'allegato da un file protetto da password proprietario/utente:

`pdfdetach -save {{numero}} {{-opw|-upw}} {{password}} {{percorso/input.pdf}}`
