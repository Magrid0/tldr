# rev

> Inverte una riga di testo o un file.
> Maggiori informazioni: <https://manned.org/rev>.

- Inverte il testo digitato nel terminale:

`rev`

- Inverte la stringa di testo "hello":

`echo "hello" | rev`

- Inverte un intero file e stampa su `stdout`:

`rev {{path/to/file}}`

- Usa '\0' come separatore di riga (terminazione zero):

`rev {{[-0|--zero]}} {{path/to/file}}`

- Mostra aiuto:

`rev {{[-h|--help]}}`

- Mostra versione:

`rev {{[-V|--version]}}`
