# mpstat

> Segnala statistiche della CPU.
> Maggiori informazioni: <https://manned.org/mpstat>.

- Mostra le statistiche della CPU ogni 2 secondi:

`mpstat {{2}}`

- Mostra 5 report, uno dopo l'altro, a intervalli di 2 secondi:

`mpstat {{2}} {{5}}`

- Mostra 5 report, uno dopo l'altro, da un processore specifico, a intervalli di 2 secondi:

`mpstat -P {{0}} {{2}} {{5}}`
