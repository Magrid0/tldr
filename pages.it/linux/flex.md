# flex

> Generatore di analizzatori lessicali.
> Data la specifica per un analizzatore lessicale, genera codice C che lo implementa.
> Maggiori informazioni: <https://manned.org/flex>.

- Genera un analizzatore da un file Lex, salvandolo nel file `lex.yy.c`:

`flex {{analyzer.l}}`

- Scrive l'analizzatore su `stdout`:

`flex {{[-t|--stdout]}} {{analyzer.l}}`

- Specifica il file di output:

`flex {{analyzer.l}} {{[-o|--outfile]}} {{analyzer.c}}`

- Genera uno scanner batch invece di uno scanner interattivo:

`flex {{[-B|--batch]}} {{analyzer.l}}`

- Compila un file C generato da Lex:

`cc {{path/to/lex.yy.c}} -o {{executable}}`
