# fcrackzip

> Utility per la decodifica delle password di archivi ZIP.
> Maggiori informazioni: <https://manned.org/fcrackzip>.

- Decodifica una password con una lunghezza da 4 a 8 caratteri contenente solo caratteri alfanumerici (l'ordine è importante):

`fcrackzip {{[-b|--brute-force]}} {{[-l|--length]}} 4-8 {{[-c|--charset]}} aA1 {{archive}}`

- Decodifica una password in modalità verbosa con una lunghezza di 3 caratteri contenente solo caratteri minuscoli, `$` e `%`:

`fcrackzip {{[-v|--verbose]}} {{[-b|--brute-force]}} {{[-l|--length]}} 3 {{[-c|--charset]}} a:$% {{archive}}`

- Decodifica una password contenente solo caratteri minuscoli e speciali:

`fcrackzip {{[-b|--brute-force]}} {{[-l|--length]}} 4 {{[-c|--charset]}} a! {{archive}}`

- Decodifica una password contenente solo cifre, partendo dalla password `12345`:

`fcrackzip {{[-b|--brute-force]}} {{[-l|--length]}} 5 {{[-c|--charset]}} 1 {{[-p|--init-password]}} 12345 {{archive}}`

- Decodifica una password utilizzando una wordlist:

`fcrackzip {{[-u|--use-unzip]}} {{[-D|--dictionary]}} {{[-p|--init-password]}} {{wordlist}} {{archive}}`

- Valuta le prestazioni di decodifica:

`fcrackzip {{[-B|--benchmark]}}`
