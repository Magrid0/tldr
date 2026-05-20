# e4defrag

> Deframmenta un filesystem ext4.
> Maggiori informazioni: <https://manned.org/e4defrag>.

- Deframmenta il filesystem:

`e4defrag {{/dev/sdXN}}`

- Mostra quanto è frammentato un filesystem:

`e4defrag -c {{/dev/sdXN}}`

- Stampa gli errori e il conteggio della frammentazione prima e dopo ogni file:

`e4defrag -v {{/dev/sdXN}}`
