# fstrim

> Scarta i blocchi inutilizzati su un filesystem montato.
> Supportato solo da dispositivi a memoria flash come SSD e schede microSD.
> Maggiori informazioni: <https://manned.org/fstrim>.

- Scarta i blocchi inutilizzati su tutte le partizioni montate che lo supportano:

`sudo fstrim {{[-a|--all]}}`

- Scarta i blocchi inutilizzati su una partizione specificata:

`sudo fstrim {{/}}`

- Mostra le statistiche dopo il taglio:

`sudo fstrim {{[-v|--verbose]}} {{/}}`
