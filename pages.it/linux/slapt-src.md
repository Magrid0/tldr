# slapt-src

> Un'utilità per automatizzare la costruzione di slackbuilds.
> Le fonti SlackBuild devono essere configurate nel file slapt-srcrc.
> Maggiori informazioni: <https://github.com/jaos/slapt-src>.

- Aggiorna la lista degli slackbuilds e versioni disponibili:

`slapt-src {{[-u|--update]}}`

- Elenca tutti gli slackbuilds disponibili:

`slapt-src {{[-l|--list]}}`

- Scarica, compila e installa gli slackbuild(s) specificati:

`slapt-src {{[-i|--install]}} {{nome_slackbuild}}`

- Cerca slackbuilds per nome o descrizione:

`slapt-src {{[-s|--search]}} {{termine_ricerca}}`

- Mostra informazioni su uno slackbuild:

`slapt-src {{[-w|--show]}} {{nome_slackbuild}}`
