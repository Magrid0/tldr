# aurpublish

> Pubblica pacchetti dell'Arch User Repository.
> Maggiori informazioni: <https://github.com/eli-schwartz/aurpublish/blob/master/doc/aurpublish.1.asciidoc>.

- Verifica l'integrità del `PKGBUILD`, genera `.SRCINFO`, crea un modello di messaggio di commit e pubblica il pacchetto nell'AUR:

`aurpublish {{nome_pacchetto}}`

- Aggiunge githook al repository corrente:

`aurpublish setup`

- Mostra aiuto:

`aurpublish {{[-h|--help]}}`
