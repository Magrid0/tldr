# pacdiff

> Utilità di manutenzione per file `.pacorig`, `.pacnew` e `.pacsave` creati da `pacman`.
> Maggiori informazioni: <https://manned.org/pacdiff>.

- Esamina i file che necessitano manutenzione in modalità interattiva:

`pacdiff`

- Usa sudo e sudoedit per rimuovere e unire file:

`pacdiff {{[-s|--sudo]}}`

- Esamina i file che necessitano manutenzione, creando backup `.bak` dell'originale se si sceglie `(O)verwrite`:

`pacdiff {{[-s|--sudo]}} {{[-b|--backup]}}`

- Usa un editor specifico per visualizzare e unire file di configurazione (predefinito è `vim -d`):

`DIFFPROG={{editor}} pacdiff`

- Cerca file di configurazione con `locate` invece di usare il database di `pacman`:

`pacdiff {{[-l|--locate]}}`

- Mostra aiuto:

`pacdiff {{[-h|--help]}}`
