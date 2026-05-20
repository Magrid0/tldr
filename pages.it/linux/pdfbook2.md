# pdfbook2

> Crea un libretto PDF stampabile fronte-retro da un PDF.
> Nota: Il libretto deve essere stampato fronte-retro in modalità orizzontale, capovolto sul lato lungo.
> Maggiori informazioni: <https://github.com/jenom/pdfbook2#examples>.

- Crea un libretto chiamato `file-book.pdf` con impostazioni predefinite:

`pdfbook2 {{percorso/del/file.pdf}}`

- Crea un libretto con formato carta A4:

`pdfbook2 {{[-p|--paper]}} a4paper {{percorso/del/file.pdf}}`

- Crea un libretto con margine interno ridotto a 50 pixel (predefinito = 150px):

`pdfbook2 {{[-p|--paper]}} a4paper {{[-i|--inner-margin]}} 50 {{percorso/del/file.pdf}}`

- Organizza un file grande con segnature di stampa per la rilegatura in un libretto più grande (le segnature devono essere divisibili per 4):

`pdfbook2 {{[-p|--paper]}} a4paper --signature {{24}} {{percorso/del/file.pdf}}`
