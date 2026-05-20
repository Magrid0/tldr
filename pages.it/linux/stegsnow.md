# stegsnow

> Strumento di steganografia per nascondere ed estrarre messaggi in file di testo codificati come tabulazioni e spazi.
> Maggiori informazioni: <https://darkside.com.au/snow/manual.html>.

- Estrae il [m]essaggio da un file:

`stegsnow {{percorso/del/file.txt}}`

- Estrae il [m]essaggio [C]ompresso e protetto da [p]assword da un file:

`stegsnow -C -p {{password}} {{percorso/del/file.txt}}`

- Determina la capacità di archiviazione approssimativa [S] con lunghezza [l]inea inferiore a 72 per il file:

`stegsnow -S -l 72 {{percorso/del/file.txt}}`

- Nasconde il [m]essaggio nel testo da un file e lo salva nel risultato:

`stegsnow -m '{{messaggio}}' {{percorso/del/file.txt}} {{percorso/del/risultato.txt}}`

- Nasconde il contenuto del [f]ile del messaggio [C]ompresso nel testo da un file e lo salva nel risultato:

`stegsnow -C -f '{{percorso/del/messaggio.txt}}' {{percorso/del/file.txt}} {{percorso/del/risultato.txt}}`

- Nasconde il [m]essaggio [C]ompresso e protetto da [p]assword nel testo da un file e lo salva nel risultato:

`stegsnow -C -p {{password}} -m '{{messaggio}}' {{percorso/del/file.txt}} {{percorso/del/risultato.txt}}`
