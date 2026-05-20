# toybox

> Strumento multiuso che fornisce molte utility Unix standard.
> Comunemente usato in Android e sistemi Linux embedded.
> Maggiori informazioni: <https://landley.net/toybox/>.

- Elenca tutti i comandi Toybox disponibili:

`toybox`

- Esegui esplicitamente un comando Toybox (utile se esiste un altro comando con lo stesso nome in `$PATH`):

`toybox {{comando}} {{argomenti}}`

- Elenca i file nella directory corrente:

`toybox ls`

- Rimuovi un file:

`toybox rm {{percorso/del/file}}`

- Mostra le informazioni di aiuto per un comando specifico:

`toybox {{comando}} --help`

- Mostra versione:

`toybox --version`
