# trashy

> Un'alternativa a `rm` e `trash-cli` scritta in Rust.
> Maggiori informazioni: <https://github.com/oberblastmeister/trashy#usage>.

- Sposta un file specifico nel cestino:

`trash {{percorso/del/file}}`

- Sposta file specifici nel cestino:

`trash {{percorso/del/file1 percorso/del/file2 ...}}`

- Elenca gli elementi nel cestino:

`trash list`

- Ripristina un file specifico dal cestino:

`trash restore {{file}}`

- Rimuovi un file specifico dal cestino:

`trash empty {{file}}`

- Ripristina tutti i file dal cestino:

`trash restore --all`

- Rimuovi tutti i file dal cestino:

`trash empty --all`
