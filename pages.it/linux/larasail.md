# larasail

> Gestisce Laravel su server Digital Ocean.
> Maggiori informazioni: <https://github.com/thedevdojo/larasail#setup-your-server>.

- Configura il server con le dipendenze Laravel usando la versione PHP predefinita:

`larasail setup`

- Configura il server con le dipendenze Laravel usando una versione PHP specifica:

`larasail setup {{php71}}`

- Aggiunge un nuovo sito Laravel:

`larasail host {{domain}} {{path/to/site_directory}}`

- Recupera la password utente Larasail:

`larasail pass`

- Recupera la password MySQL Larasail:

`larasail mysqlpass`
