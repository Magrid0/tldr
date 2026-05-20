# whatis

> Mostra descrizioni di una riga dalle pagine di manuale.
> Vedi anche: `man`, `whereis`.
> Maggiori informazioni: <https://manned.org/whatis>.

- Mostra una descrizione da una pagina di manuale:

`whatis {{comando}}`

- Non troncare la descrizione alla fine della riga:

`whatis {{[-l|--long]}} {{comando}}`

- Mostra descrizioni per tutti i comandi che corrispondono a un glob:

`whatis {{[-w|--wildcard]}} {{net*}}`

- Cerca nelle descrizioni delle pagine di manuale con una `regex`:

`whatis {{[-r|--regex]}} '{{wish[0-9]\.[0-9]}}'`

- Mostra descrizioni in una lingua specifica:

`whatis {{[-L|--locale]}} {{en}} {{comando}}`
