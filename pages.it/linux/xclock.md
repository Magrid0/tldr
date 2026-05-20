# xclock

> Mostra l'ora in forma analogica o digitale.
> Maggiori informazioni: <https://manned.org/xclock>.

- Mostra un orologio analogico:

`xclock`

- Mostra un orologio digitale a 24 ore con solo ore e minuti:

`xclock -digital -brief`

- Mostra un orologio digitale usando una stringa di formato strftime (vedi strftime(3)):

`xclock -digital -strftime {{formato}}`

- Mostra un orologio digitale a 24 ore con ore, minuti e secondi che si aggiorna ogni secondo:

`xclock -digital -strftime '%H:%M:%S' -update 1`

- Mostra un orologio digitale a 12 ore con solo ore e minuti:

`xclock -digital -twelve -brief`
