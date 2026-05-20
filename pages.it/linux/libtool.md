# libtool

> Uno script generico di supporto per librerie che nasconde la complessità dell'uso di librerie condivise dietro un'interfaccia coerente e portabile.
> Maggiori informazioni: <https://www.gnu.org/software/libtool/manual/libtool.html#Invoking-libtool>.

- Compila un file sorgente in un oggetto `libtool`:

`libtool {{[c|compile]}} gcc {{[-c|--compile]}} {{path/to/source.c}} {{[-o|--output]}} {{path/to/source.lo}}`

- Crea una libreria o un eseguibile:

`libtool {{[l|link]}} gcc {{[-o|--output]}} {{path/to/library.lo}} {{path/to/source.lo}}`

- Imposta automaticamente il percorso della libreria in modo che un altro programma possa usare programmi o librerie generati da `libtool` non installati:

`libtool {{[e|execute]}} gdb {{path/to/program}}`

- Installa una libreria condivisa:

`libtool {{[i|install]}} cp {{path/to/library.la}} {{path/to/installation_directory}}`

- Completa l'installazione delle librerie `libtool` sul sistema:

`libtool {{[f|finish]}} {{path/to/installation_directory}}`

- Elimina librerie o eseguibili installati:

`libtool {{[u|uninstall]}} {{path/to/installed_library.la}}`

- Elimina librerie o eseguibili non installati:

`libtool {{[cl|clean]}} rm {{path/to/source.lo}} {{path/to/library.la}}`
