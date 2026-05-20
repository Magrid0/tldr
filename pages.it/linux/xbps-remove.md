# xbps-remove

> Utilità XBPS per rimuovere pacchetti.
> Vedi anche: `xbps`.
> Maggiori informazioni: <https://manned.org/xbps-remove>.

- Rimuovi un pacchetto:

`xbps-remove {{pacchetto}}`

- Rimuovi un pacchetto e le sue dipendenze:

`xbps-remove {{[-R|--recursive]}} {{pacchetto}}`

- Rimuovi i pacchetti orfani (installati come dipendenze ma non più richiesti da alcun pacchetto):

`xbps-remove {{[-o|--remove-orphans]}}`

- Rimuovi i pacchetti obsoleti dalla cache:

`xbps-remove {{[-O|--clean-cache]}}`
