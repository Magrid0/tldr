# speedread

> Un lettore veloce simile a Spritz.
> Mostra il testo usando la Presentazione Visiva Seriale Rapida (RSVP) parola per parola.
> Maggiori informazioni: <https://github.com/pasky/speedread>.

- Legge un file di testo a una velocità specifica:

`cat {{percorso/del/file.txt}} | speedread -wpm {{250}}`

- Riprende da una riga specifica:

`cat {{percorso/del/file.txt}} | speedread -resume {{5}}`

- Mostra più parole alla volta:

`cat {{percorso/del/file.txt}} | speedread -multiword`

- Rallenta del 10% durante la sessione di lettura:

`<[>`

- Accelera del 10% durante la sessione di lettura:

`<]>`

- Mette in pausa e mostra le ultime righe come contesto:

`<Space>`
