# pdftohtml

> Converte file PDF in HTML, XML e immagini PNG.
> Maggiori informazioni: <https://manned.org/pdftohtml>.

- Converte un file PDF in un file HTML:

`pdftohtml {{percorso/del/file.pdf}} {{percorso/del/file_output.html}}`

- Ignora le immagini nel file PDF:

`pdftohtml -i {{percorso/del/file.pdf}} {{percorso/del/file_output.html}}`

- Genera un singolo file HTML che include tutte le pagine PDF:

`pdftohtml -s {{percorso/del/file.pdf}} {{percorso/del/file_output.html}}`

- Converte un file PDF in un file XML:

`pdftohtml -xml {{percorso/del/file.pdf}} {{percorso/del/file_output.xml}}`
