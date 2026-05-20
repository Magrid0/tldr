# just

> Un runtime JavaScript V8 per Linux.
> Maggiori informazioni: <https://github.com/just-js/just>.

- Avvia una REPL (shell interattiva):

`just`

- Esegue un file JavaScript:

`just {{path/to/file.js}}`

- Valuta codice JavaScript passandolo come argomento:

`just eval "{{code}}"`

- Inizializza un nuovo progetto in una directory con lo stesso nome:

`just init {{project_name}}`

- Compila un'applicazione JavaScript in un eseguibile:

`just build {{path/to/file.js}} --static`
