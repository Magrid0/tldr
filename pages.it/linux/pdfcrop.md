# pdfcrop

> Rileva e rimuove i margini in ogni pagina di un file PDF.
> Maggiori informazioni: <https://github.com/ho-tex/pdfcrop>.

- Rileva e rimuove automaticamente il margine per ogni pagina in un file PDF:

`pdfcrop {{percorso/file_input.pdf}} {{percorso/file_output.pdf}}`

- Imposta i margini di ogni pagina a un valore specifico:

`pdfcrop {{percorso/file_input.pdf}} --margins '{{sinistra}} {{alto}} {{destra}} {{basso}}' {{percorso/file_output.pdf}}`

- Imposta i margini di ogni pagina a un valore specifico, usando lo stesso valore per sinistra, alto, destra e basso:

`pdfcrop {{percorso/file_input.pdf}} --margins {{300}} {{percorso/file_output.pdf}}`

- Usa un bounding box definito dall'utente per il ritaglio invece di rilevarlo automaticamente:

`pdfcrop {{percorso/file_input.pdf}} --bbox '{{sinistra}} {{alto}} {{destra}} {{basso}}' {{percorso/file_output.pdf}}`

- Usa bounding box diversi definiti dall'utente per pagine pari e dispari:

`pdfcrop {{percorso/file_input.pdf}} --bbox-odd '{{sinistra}} {{alto}} {{destra}} {{basso}}' --bbox-even '{{sinistra}} {{alto}} {{destra}} {{basso}}' {{percorso/file_output.pdf}}`

- Rileva automaticamente i margini usando una risoluzione inferiore per migliori prestazioni:

`pdfcrop {{percorso/file_input.pdf}} --resolution {{72}} {{percorso/file_output.pdf}}`
