# ldd

> Mostra le dipendenze delle librerie condivise di un binario.
> Non usare su un binario non fidato, usa objdump per quello.
> Maggiori informazioni: <https://manned.org/ldd>.

- Mostra le dipendenze delle librerie condivise di un binario:

`ldd {{path/to/binary}}`

- Mostra tutte le informazioni sulle dipendenze:

`ldd {{[-v|--verbose]}} {{path/to/binary}}`

- Mostra le dipendenze dirette inutilizzate:

`ldd {{[-u|--unused]}} {{path/to/binary}}`

- Segnala oggetti dati mancanti ed esegue rilocazioni dati:

`ldd {{[-d|--data-relocs]}} {{path/to/binary}}`

- Segnala oggetti dati e funzioni mancanti ed esegue rilocazioni per entrambi:

`ldd {{[-r|--function-relocs]}} {{path/to/binary}}`
