# pacconf

> Interroga e mostra le opzioni di configurazione di pacman, mostrando l'intera configurazione o i valori specifici delle direttive come interpretati da pacman.
> Maggiori informazioni: <https://github.com/andrewgregory/pacutils/blob/master/doc/pacconf.pod>.

- Mostra l'intera configurazione di pacman interpretata:

`pacconf`

- Elenca i repository configurati:

`pacconf --repo-list`

- Mostra sempre i nomi delle direttive anche se viene fornita una sola direttiva:

`pacconf --verbose {{direttiva}}`

- Mostra solo il primo valore delle opzioni con valori multipli:

`pacconf --single`

- Mostra aiuto:

`pacconf --help`

- Mostra versione:

`pacconf --version`
