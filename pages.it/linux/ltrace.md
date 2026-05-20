# ltrace

> Mostra le chiamate alle librerie dinamiche di un processo.
> Maggiori informazioni: <https://manned.org/ltrace>.

- Stampa (traccia) le chiamate alle librerie di un programma binario:

`ltrace {{path/to/program}}`

- Conta le chiamate alle librerie. Stampa un comodo riepilogo alla fine:

`ltrace -c {{path/to/program}}`

- Traccia le chiamate a malloc e free, omettendo quelle fatte da libc:

`ltrace -e malloc+free-@libc.so* {{path/to/program}}`

- Scrivi su file invece che sul terminale:

`ltrace {{[-o|--output]}} {{file}} {{path/to/program}}`
