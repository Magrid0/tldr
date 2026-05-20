# qtchooser

> Un wrapper usato per selezionare tra versioni binarie di sviluppo Qt.
> Maggiori informazioni: <https://manned.org/qtchooser>.

- Elenca le versioni Qt disponibili dai file di configurazione:

`qtchooser --list-versions`

- Stampa le informazioni sull'ambiente:

`qtchooser --print-env`

- Esegue lo strumento specificato usando la versione Qt specificata:

`qtchooser --run-tool={{tool}} --qt={{version_name}}`

- Aggiunge una voce di versione Qt per poter scegliere:

`qtchooser --install {{version_name}} {{path/to/qmake}}`

- Mostra aiuto:

`qtchooser --help`
