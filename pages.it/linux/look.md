# look

> Mostra le righe che iniziano con un prefisso in un file.
> Nota: Le righe nel file devono essere ordinate.
> Vedi anche: `grep`, `sort`.
> Maggiori informazioni: <https://manned.org/look>.

- Cerca righe che iniziano con un prefisso specifico in un file specifico:

`look {{prefix}} {{path/to/file}}`

- Cerca senza distinzione tra maiuscole e minuscole solo su caratteri vuoti e alfanumerici:

`look {{[-f|--ignore-case]}} {{[-d|--alphanum]}} {{prefix}} {{path/to/file}}`

- Specifica un carattere di terminazione della stringa (spazio per impostazione predefinita):

`look {{[-t|--terminate]}} {{,}}`

- Cerca in `/usr/share/dict/words` (`--ignore-case` e `--alphanum` sono impliciti):

`look {{prefix}}`

- Cerca in `/usr/share/dict/web2` (`--ignore-case` e `--alphanum` sono impliciti):

`look {{[-a|--alternative]}} {{prefix}}`
