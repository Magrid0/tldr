# mcookie

> Genera numeri esadecimali casuali a 128 bit.
> Maggiori informazioni: <https://manned.org/mcookie>.

- Genera un numero casuale:

`mcookie`

- Genera un numero casuale, usando il contenuto di un file come seme per la casualità:

`mcookie {{[-f|--file]}} {{path/to/file}}`

- Genera un numero casuale, usando un numero specifico di byte da un file come seme per la casualità:

`mcookie {{[-f|--file]}} {{path/to/file}} {{[-m|--max-size]}} {{number_of_bytes}}`

- Stampa i dettagli della casualità usata, come l'origine e il seme per ogni fonte:

`mcookie {{[-v|--verbose]}}`
