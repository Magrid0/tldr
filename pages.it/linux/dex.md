# dex

> DesktopEntry Execution (DEX) è un programma per generare ed eseguire file DesktopEntry di tipo Application.
> Maggiori informazioni: <https://github.com/jceb/dex#dex>.

- Esegue tutti i programmi nelle cartelle di avvio automatico:

`dex {{[-a|--autostart]}}`

- Esegue tutti i programmi nelle cartelle specificate:

`dex {{[-a|--autostart]}} {{[-s|--search-paths]}} {{path/to/directory1}}:{{path/to/directory2}}:{{path/to/directory3}}:`

- Mostra l'anteprima dei programmi che verrebbero eseguiti in un avvio automatico GNOME:

`dex {{[-a|--autostart]}} {{[-e|--environment]}} {{GNOME}}`

- Mostra l'anteprima dei programmi che verrebbero eseguiti in un avvio automatico regolare:

`dex {{[-a|--autostart]}} {{[-d|--dry-run]}}`

- Mostra l'anteprima del valore della proprietà DesktopEntry `Name`:

`dex {{[-p|--property]}} {{Name}} {{path/to/file.desktop}}`

- Crea un DesktopEntry per un programma nella directory corrente:

`dex {{[-c|--create]}} {{path/to/file.desktop}}`

- Esegue un singolo programma (con `Terminal=true` nel file `.desktop`) nel terminale indicato:

`dex --term {{terminal}} {{path/to/file.desktop}}`
