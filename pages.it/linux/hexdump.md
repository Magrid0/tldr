# hexdump

> Un dump ASCII, decimale, esadecimale, ottale.
> Vedi anche: `hexyl`, `od`, `xxd`.
> Maggiori informazioni: <https://manned.org/hexdump>.

- Mostra la rappresentazione esadecimale di un file, sostituendo le linee duplicate con '*':

`hexdump {{path/to/file}}`

- Mostra l'offset di input in esadecimale e la sua rappresentazione ASCII in due colonne:

`hexdump {{[-C|--canonical]}} {{path/to/file}}`

- Mostra la rappresentazione esadecimale di un file, ma interpreta solo n byte dell'input:

`hexdump {{[-C|--canonical]}} {{[-n|--length]}} {{number_of_bytes}} {{path/to/file}}`

- Non sostituire le linee duplicate con '*':

`hexdump {{[-v|--no-squeezing]}} {{path/to/file}}`
