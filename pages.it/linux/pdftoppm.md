# pdftoppm

> Converte le pagine di documenti PDF in formati immagine Pixmap portatili.
> Maggiori informazioni: <https://manned.org/pdftoppm>.

- Specifica l'intervallo di pagine da convertire (`n` - prima pagina, `m` - ultima pagina):

`pdftoppm -f {{n}} -l {{m}} {{percorso/del/file.pdf}} {{prefisso_nome_immagine}}`

- Converte solo la prima pagina di un PDF:

`pdftoppm -singlefile {{percorso/del/file.pdf}} {{prefisso_nome_immagine}}`

- Genera un file PBM monocromatico (invece di un file PPM a colori):

`pdftoppm -mono {{percorso/del/file.pdf}} {{prefisso_nome_immagine}}`

- Genera un file PGM in scala di grigi (invece di un file PPM a colori):

`pdftoppm -gray {{percorso/del/file.pdf}} {{prefisso_nome_immagine}}`

- Genera un file PNG invece di un file PPM:

`pdftoppm -png {{percorso/del/file.pdf}} {{prefisso_nome_immagine}}`
