# pstoedit

> Converte file PDF in vari formati immagine.
> Maggiori informazioni: <http://www.calvina.de/pstoedit/pstoedit.htm>.

- Converte una pagina PDF in formato PNG o JPEG:

`pstoedit -page {{numero_pagina}} -f magick {{percorso/del/file.pdf}} {{pagina.png|pagina.jpg}}`

- Converte più pagine PDF in immagini numerate:

`pstoedit -f magick {{percorso/del/file}} {{pagina%d.png|pagina%d.jpg}}`
