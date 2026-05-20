# wipefs

> Cancella le firme di filesystem, raid o tabella delle partizioni da un dispositivo.
> Maggiori informazioni: <https://manned.org/wipefs>.

- Mostra le firme per il dispositivo specificato:

`sudo wipefs {{/dev/sdX}}`

- Cancella tutti i tipi di firma disponibili per un dispositivo specifico senza ricorsione nelle partizioni:

`sudo wipefs {{[-a|--all]}} {{/dev/sdX}}`

- Cancella tutti i tipi di firma disponibili per il dispositivo e le partizioni usando un pattern glob:

`sudo wipefs {{[-a|--all]}} {{/dev/sdX}}*`

- Esegui una prova a secco:

`sudo wipefs {{[-a|--all]}} {{[-n|--no-act]}} {{/dev/sdX}}`

- Forza la cancellazione, anche se il filesystem è montato:

`sudo wipefs {{[-a|--all]}} {{[-f|--force]}} {{/dev/sdX}}`
