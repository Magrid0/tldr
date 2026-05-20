# xbps-query

> Utilità XBPS per interrogare informazioni su pacchetti e repository.
> Vedi anche: `xbps`.
> Maggiori informazioni: <https://manned.org/xbps-query>.

- Cerca un pacchetto nei repository remoti usando un `regex` o una parola chiave (se `--regex` viene omesso):

`xbps-query {{[-s|--search]}} {{regex|keyword}} --repository --regex`

- Mostra informazioni su un pacchetto installato:

`xbps-query {{[-S|--show]}} {{pacchetto}}`

- Mostra informazioni su un pacchetto nei repository remoti:

`xbps-query {{[-S|--show]}} {{pacchetto}} --repository`

- Elenca i pacchetti registrati nel database dei pacchetti:

`xbps-query {{[-l|--list-pkgs]}}`

- Elenca i pacchetti installati esplicitamente (cioè non installati automaticamente come dipendenze):

`xbps-query {{[-m|--list-manual-pkgs]}}`
