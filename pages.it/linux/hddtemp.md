# hddtemp

> Mostra la temperatura dell'HDD tramite S.M.A.R.T.
> Maggiori informazioni: <https://manned.org/hddtemp>.

- Mostra la temperatura di un'unità specifica:

`hddtemp {{type}}:{{/dev/sdX}}`

- Mostra la temperatura di un'unità SATA assegnata a `sda`:

`hddtemp SATA:/dev/sda`

- Registra le temperature in syslog ogni `n` secondi:

`hddtemp {{[-S|--syslog]}} {{nseconds}} {{type}}:{{/dev/sdX}}`

- Mostra solo il valore numerico della temperatura senza unità:

`hddtemp {{[-n|--numeric]}} {{type}}:{{/dev/sdX}}`

- Definisce l'unità usata per indicare la temperatura:

`hddtemp {{[-u|--unit]}} {{C|F}} {{type}}:{{/dev/sdX}}`

- Attiva l'unità ATA prima di tentare di leggere la temperatura:

`hddtemp {{[-w|--wake-up]}} {{type}}:{{/dev/sdX}}`

- Entra in modalità debug per mostrare i campi S.M.A.R.T. e i loro valori:

`hddtemp {{[-D|--debug]}} {{type}}:{{/dev/sdX}}`

- Sopprime il controllo di compatibilità per i tipi di unità:

`hddtemp {{[-q|--quiet]}} {{type}}:{{/dev/sdX}}`
