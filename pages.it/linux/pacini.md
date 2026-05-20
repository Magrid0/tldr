# pacini

> Interroga file di configurazione in stile pacman.
> Maggiori informazioni: <https://github.com/andrewgregory/pacutils/blob/master/doc/pacini.pod>.

- Mostra l'intero file di configurazione analizzato (predefinito: `stdin`):

`pacini {{percorso/del/file}}`

- Elenca le sezioni configurate:

`pacini {{percorso/del/file}} --section-list`

- Mostra sempre i nomi delle direttive anche se viene fornita una sola direttiva:

`pacini {{percorso/del/file}} --verbose`

- Mostra le direttive elencate in una sezione specifica:

`pacini {{percorso/del/file}} --section {{nome_sezione}}`

- Mostra aiuto:

`pacini --help`

- Mostra versione:

`pacini --version`
