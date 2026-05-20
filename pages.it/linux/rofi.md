# rofi

> Un lanciatore di applicazioni e commutatore di finestre.
> Maggiori informazioni: <https://github.com/davatorium/rofi#manpage>.

- Mostra l'elenco delle app:

`rofi -show drun`

- Mostra l'elenco di tutti i comandi:

`rofi -show run`

- Commuta tra finestre:

`rofi -show window`

- Invia un elenco di elementi a `stdin` e stampa l'elemento selezionato su `stdout`:

`printf "{{Choice1\nChoice2\nChoice3}}" | rofi -dmenu`
