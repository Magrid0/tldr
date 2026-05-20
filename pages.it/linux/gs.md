# gs

> GhostScript, un interprete PDF e PostScript.
> Maggiori informazioni: <https://manned.org/gs>.

- Visualizza un file:

`gs -dQUIET -dBATCH {{file.pdf}}`

- Riduce la dimensione del file PDF a immagini a 150 dpi per la lettura su un e-book:

`gs -dNOPAUSE -dQUIET -dBATCH -sDEVICE=pdfwrite -dPDFSETTINGS=/ebook -sOutputFile={{output.pdf}} {{input.pdf}}`

- Converte un file PDF (pagine da 1 a 3) in un'immagine con risoluzione 150 dpi:

`gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=jpeg -r150 -dFirstPage=1 -dLastPage=3 -sOutputFile={{output_%d.jpg}} {{input.pdf}}`

- Estrae pagine da un file PDF:

`gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile={{output.pdf}} {{input.pdf}}`

- Unisce file PDF:

`gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile={{output.pdf}} {{input1.pdf}} {{input2.pdf}}`

- Converte da file PostScript a file PDF:

`gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile={{output.pdf}} {{input.ps}}`
