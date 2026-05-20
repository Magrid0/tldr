# logread

> Legge il buffer ad anello del log di `logd`.
> Maggiori informazioni: <https://openwrt.org/docs/guide-user/base-system/log.essentials>.

- Stampa il log:

`logread`

- Stampa `n` messaggi:

`logread -l {{n}}`

- Filtra i messaggi per (Keyword/`regex`):

`logread -e {{pattern}}`

- Stampa i messaggi di log mentre accadono:

`logread -f`

- Mostra aiuto:

`logread -h`
