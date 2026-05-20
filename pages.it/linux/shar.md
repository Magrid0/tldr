# shar

> Crea un archivio shell.
> Maggiori informazioni: <https://www.gnu.org/software/sharutils/manual/sharutils.html>.

- Crea uno script shell che quando eseguito estrae i file dati da sé stesso:

`shar {{[-V|--vanilla-operation]}} {{percorso/del/file1 percorso/del/file2 ...}} > {{percorso/dell/archivio.sh}}`

- Comprime i file nell'archivio:

`shar {{[-C|--compactor]}} {{xz}} {{percorso/del/file1 percorso/del/file2 ...}} > {{percorso/dell/archivio.sh}}`

- Tratta tutti i file come binari (cioè `uuencode` tutto):

`shar {{[-B|--uuencode]}} {{percorso/del/file1 percorso/del/file2 ...}} > {{percorso/dell/archivio.sh}}`

- Tratta tutti i file come testo (cioè niente `uuencode`):

`shar {{[-T|--text-files]}} {{percorso/del/file1 percorso/del/file2 ...}} > {{percorso/dell/archivio.sh}}`

- Include un nome e un segno di taglio nell'intestazione dell'archivio:

`shar {{[-n|--archive-name]}} "{{Miei file}}" {{[-c|--cut-mark]}} {{percorso/del/file1 percorso/del/file2 ...}} > {{percorso/dell/archivio.sh}}`
