# deborphan

> Mostra i pacchetti orfani su sistemi operativi che usano il gestore pacchetti APT.
> Maggiori informazioni: <https://manned.org/deborphan>.

- Mostra i pacchetti libreria (dalla sezione "libs" del repository) che non sono richiesti da altri pacchetti:

`deborphan`

- Elenca i pacchetti orfani dalla sezione "libs" e i pacchetti orfani con un nome simile a una libreria:

`deborphan --guess-all`

- Trova pacchetti che sono solo raccomandati o suggeriti (ma non richiesti) da un altro pacchetto:

`deborphan {{[-n|--nice-mode]}}`
