# ntpq

> Interroga il demone NTP (Network Time Protocol).
> Maggiori informazioni: <https://manned.org/ntpq>.

- Avvia `ntpq` in modalità interattiva:

`ntpq`

- Stampa un elenco di peer NTP:

`ntpq {{[-p|--peers]}}`

- Stampa un elenco di peer NTP senza risolvere i nomi host dagli indirizzi IP:

`ntpq {{[-n|--numeric]}} {{[-p|--peers]}}`

- Usa `ntpq` in modalità debug:

`ntpq {{[-d|--debug-level]}}`

- Stampa i valori delle variabili di sistema NTP:

`ntpq {{[-c|--command]}} {{rv}}`
