# handlr

> Gestisce le applicazioni predefinite.
> Maggiori informazioni: <https://github.com/chmln/handlr#usage>.

- Apre un URL nell'applicazione predefinita:

`handlr open {{https://example.com}}`

- Apre un PDF nel visualizzatore PDF predefinito:

`handlr open {{path/to/file.pdf}}`

- Imposta `imv` come applicazione predefinita per i file PNG:

`handlr set {{.png}} {{imv.desktop}}`

- Imposta MPV come applicazione predefinita per tutti i file audio:

`handlr set '{{audio/*}}' {{mpv.desktop}}`

- Elenca tutte le app predefinite:

`handlr list`

- Mostra l'applicazione predefinita per i file PNG:

`handlr get {{.png}}`
