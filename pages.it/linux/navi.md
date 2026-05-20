# navi

> Uno strumento interattivo di cheat sheet per la riga di comando e lanciatori di applicazioni.
> Maggiori informazioni: <https://github.com/denisidoro/navi>.

- Sfoglia tutti i cheat sheet disponibili:

`navi`

- Sfoglia il cheat sheet per `navi` stesso:

`navi fn welcome`

- Stampa un comando dal cheat sheet senza eseguirlo:

`navi --print`

- Emette il codice sorgente del widget della shell (rileva automaticamente la shell se possibile, ma può anche essere specificato manualmente):

`navi widget {{shell}}`

- Seleziona automaticamente ed esegue lo snippet che corrisponde meglio a una query:

`navi {{[-q|--query]}} '{{query}}' --best-match`
