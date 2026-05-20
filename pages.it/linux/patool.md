# patool

> Gestore di file di archivio.
> Vari formati di archivio possono essere creati, estratti, testati, elencati, cercati, reimpacchettati e confrontati.
> Maggiori informazioni: <https://github.com/wummel/patool/blob/master/doc/patool.txt>.

- Estrai un archivio:

`patool extract {{percorso/dell/archivio}}`

- Crea un archivio:

`patool create {{percorso/dell/archivio}} {{percorso/del/file_o_directory1 percorso/del/file_o_directory2 ...}}`

- Elenca i contenuti di un archivio:

`patool list {{percorso/dell/archivio}}`

- Confronta i contenuti di due archivi e mostra le differenze su `stdout`:

`patool diff {{percorso/dell/archivio1}} {{percorso/dell/archivio2}}`

- Cerca una stringa all'interno dei contenuti di un archivio:

`patool search {{percorso/dell/archivio}}`
