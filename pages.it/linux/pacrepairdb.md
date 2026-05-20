# pacrepairdb

> Ripara le voci del database danneggiate nel database libalpm.
> Maggiori informazioni: <https://github.com/andrewgregory/pacutils/blob/master/doc/pacrepairdb.pod>.

- Esegue una riparazione base su un pacchetto specifico:

`pacrepairdb {{nome_pacchetto}}`

- Aggiorna le voci del database senza estrarre o rimuovere pacchetti:

`pacrepairdb {{nome_pacchetto}} --dbonly`

- Mostra i pacchetti da riparare e i pacchetti in cache da usare senza apportare modifiche:

`pacrepairdb {{nome_pacchetto}} --print-only`

- Mostra informazioni aggiuntive di progresso e debug:

`pacrepairdb {{nome_pacchetto}} --verbose`

- Mostra aiuto:

`pacrepairdb --help`

- Mostra versione:

`pacrepairdb --version`
