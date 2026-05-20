# kpackagetool5

> KPackage Manager: installa, elenca, rimuove pacchetti Plasma.
> Maggiori informazioni: <https://manned.org/kpackagetool5>.

- Elenca tutti i tipi di pacchetto conosciuti che possono essere installati:

`kpackagetool5 --list-types`

- Installa il pacchetto da una directory:

`kpackagetool5 {{[-t|--type]}} {{package_type}} {{[-i|--install]}} {{path/to/directory}}`

- Aggiorna un pacchetto installato da una directory:

`kpackagetool5 {{[-t|--type]}} {{package_type}} {{[-u|--upgrade]}} {{path/to/directory}}`

- Elenca i plasmoid installati (`--global` per tutti gli utenti):

`kpackagetool5 {{[-t|--type]}} Plasma/Applet {{[-l|--list]}} {{[-g|--global]}}`

- Rimuove un plasmoid per nome:

`kpackagetool5 {{[-t|--type]}} Plasma/Applet {{[-r|--remove]}} "{{name}}"`
