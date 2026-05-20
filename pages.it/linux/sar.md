# sar

> Monitora le prestazioni di vari sottosistemi Linux.
> Maggiori informazioni: <https://manned.org/sar>.

- Riporta I/O e tasso di trasferimento emessi verso dispositivi fisici, uno al secondo (premi `<Ctrl c>` per uscire):

`sar -b {{1}}`

- Riporta un totale di 10 statistiche dei dispositivi di rete, una ogni 2 secondi:

`sar -n DEV {{2}} {{10}}`

- Riporta l'utilizzo della CPU, una ogni 2 secondi:

`sar -u ALL {{2}}`

- Riporta un totale di 20 statistiche di utilizzo della memoria, una al secondo:

`sar -r ALL {{1}} {{20}}`

- Riporta la lunghezza della coda di esecuzione e i carichi medi, una al secondo:

`sar -q {{1}}`

- Riporta le statistiche di paging, una ogni 5 secondi:

`sar -B {{5}}`
