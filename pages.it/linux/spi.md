# spi

> Un meta gestore di pacchetti che gestisce sia pacchetti che slackbuilds.
> Maggiori informazioni: <https://github.com/gapan/spi/blob/master/man/spi.t2t>.

- Aggiorna la lista dei pacchetti e slackbuilds disponibili:

`spi {{[-u|--update]}}`

- Installa un pacchetto o slackbuild:

`spi {{[-i|--install]}} {{pacchetto/nome_slackbuild}}`

- Aggiorna tutti i pacchetti installati alle ultime versioni disponibili:

`spi {{[-U|--upgrade]}}`

- Cerca pacchetti o slackbuilds per nome o descrizione:

`spi {{termini_ricerca}}`

- Mostra informazioni su un pacchetto o slackbuild:

`spi --show {{pacchetto/nome_slackbuild}}`

- Pulisce le cache locali di pacchetti e slackbuild:

`spi --clean`
