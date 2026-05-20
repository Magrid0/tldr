# loadkeys

> Carica la mappa dei tasti del kernel per la console.
> Vedi anche: `localectl`.
> Maggiori informazioni: <https://manned.org/loadkeys>.

- Carica una disposizione di tastiera specifica per la console corrente:

`sudo loadkeys {{en|de|fi|dvorak|defkeymap|...}}`

- Carica una mappa predefinita:

`sudo loadkeys {{[-d|--default]}}`

- Stampa la tabella del kernel di una mappa su `stdout`:

`loadkeys {{[-m|--mktable]}} {{en|de|fi|...}}`

- Stampa il formato binario di una mappa su `stdout`:

`loadkeys {{[-b|--bkeymap]}} {{en|de|fi|...}}`

- Cerca e analizza la mappa senza azione:

`loadkeys {{[-p|--parse]}} {{en|de|fi|...}}`

- Carica una mappa da `stdin`, sopprimendo tutto l'output:

`{{command}} | sudo loadkeys {{[-q|--quiet]}}`

- Imposta una mappa per una console specifica:

`sudo loadkeys {{[-C|--console]}} {{/dev/ttyN}} {{uk}}`

- Carica una mappa dal file specificato per la console:

`sudo loadkeys {{[-C|--console]}} {{/dev/ttyN}} /{{path/to/file}}`
