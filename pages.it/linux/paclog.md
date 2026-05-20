# paclog

> Filtra le voci del log di pacman.
> Maggiori informazioni: <https://github.com/andrewgregory/pacutils/blob/master/doc/paclog.pod>.

- Mostra l'intero log di pacman:

`paclog`

- Mostra le voci di comando registrate in stile pacman:

`paclog --commandline`

- Mostra eventi di log per un pacchetto specifico:

`paclog --package {{nome_pacchetto}}`

- Mostra azioni sui pacchetti di un tipo specifico:

`paclog --action {{install|reinstall|upgrade|downgrade|remove|all}}`

- Mostra solo errori, avvisi e note:

`paclog --warnings`

- Mostra l'elenco dei pacchetti installati secondo il log:

`paclog --pkglist`

- Mostra aiuto:

`paclog --help`

- Mostra versione:

`paclog --version`
