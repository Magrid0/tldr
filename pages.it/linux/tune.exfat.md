# tune.exfat

> Regola i parametri regolabili del filesystem su un filesystem exFAT.
> Maggiori informazioni: <https://manned.org/tune.exfat>.

- Stampa l'etichetta del volume di un filesystem:

`tune.exfat {{[-l|--print-label]}} {{/dev/sdXY}}`

- Imposta l'etichetta del volume di un filesystem:

`tune.exfat {{[-L|--set-label]}} {{nuova_etichetta}} {{/dev/sdXY}}`

- Stampa il GUID del volume di un filesystem:

`tune.exfat {{[-u|--print-guid]}} {{/dev/sdXY}}`

- Imposta il GUID del volume di un filesystem:

`tune.exfat {{[-U|--set-guid]}} {{nuovo_guid}} {{/dev/sdXY}}`

- Stampa il seriale del volume di un filesystem:

`tune.exfat {{[-i|--print-serial]}} {{/dev/sdXY}}`

- Imposta il seriale del volume di un filesystem:

`tune.exfat {{[-I|--set-serial]}} {{nuovo_seriale}} {{/dev/sdXY}}`
