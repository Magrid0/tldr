# addr2line

> Converte indirizzi di un binario in nomi di file e numeri di riga.
> Maggiori informazioni: <https://manned.org/addr2line>.

- Mostra il nome del file e il numero di riga del codice sorgente da un indirizzo di istruzione di un eseguibile:

`addr2line {{[-e|--exe]}} {{path/to/eseguibile}} {{indirizzo}}`

- Mostra il nome della funzione, il nome del file e il numero di riga:

`addr2line {{[-e|--exe]}} {{path/to/eseguibile}} {{[-f|--functions]}} {{indirizzo}}`

- Demangla il nome della funzione per codice C++:

`addr2line {{[-e|--exe]}} {{path/to/eseguibile}} {{[-f|--functions]}} {{[-C|--demangle]}} {{indirizzo}}`
