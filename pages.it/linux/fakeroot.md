# fakeroot

> Esegue un comando in un ambiente che simula i privilegi di root per la manipolazione dei file.
> Maggiori informazioni: <https://manned.org/fakeroot>.

- Avvia la shell predefinita come fakeroot:

`fakeroot`

- Esegue un comando come fakeroot:

`fakeroot -- {{command}} {{command_arguments}}`

- Esegue un comando come fakeroot e [s]alva l'ambiente su un file all'uscita:

`fakeroot -s {{path/to/file}} -- {{command}} {{command_arguments}}`

- Carica un ambiente fakeroot ed esegue un comando come fakeroot:

`fakeroot -i {{path/to/file}} -- {{command}} {{command_arguments}}`

- Esegue un comando mantenendo la proprietà reale dei file invece di simulare che siano di proprietà di root:

`fakeroot {{[-u|--unknown-is-real]}} -- {{command}} {{command_arguments}}`

- Mostra aiuto:

`fakeroot {{[-h|--help]}}`
