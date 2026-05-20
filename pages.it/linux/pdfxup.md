# pdfxup

> Disposizione N-up di pagine PDF.
> N-up significa mettere più pagine su una singola pagina ridimensionandole e ruotandole in una griglia.
> Maggiori informazioni: <https://ctan.org/pkg/pdfxup>.

- Crea un PDF 2-up:

`pdfxup {{[-o|--output]}} {{percorso/output.pdf}} {{percorso/input.pdf}}`

- Crea un PDF con 3 colonne e 2 righe per pagina:

`pdfxup {{[-x|--columns]}} {{3}} {{[-y|--rows]}} {{2}} {{[-o|--output]}} {{percorso/output.pdf}} {{percorso/input.pdf}}`

- Crea un PDF in modalità libretto (2-up, pagine ordinate per formare un libro quando piegate):

`pdfxup {{[-b|--booklet]}} {{[-o|--output]}} {{percorso/output.pdf}} {{percorso/input.pdf}}`
