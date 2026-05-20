# systemd-cgtop

> Mostra i migliori control group della gerarchia locale dei control group Linux, ordinati per carico di CPU, memoria o I/O disco.
> Vedi anche: `top`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-cgtop.html>.

- Avvia una visualizzazione interattiva:

`systemd-cgtop`

- Cambia l'ordinamento:

`systemd-cgtop --order {{cpu|memory|path|tasks|io}}`

- Mostra l'utilizzo della CPU per tempo invece che in percentuale:

`systemd-cgtop --cpu=percentage`

- Cambia l'intervallo di aggiornamento in secondi (o in una di queste unità di tempo: `ms`, `us`, `min`):

`systemd-cgtop {{[-d|--delay]}} {{intervallo}}`

- Conta solo i processi in spazio utente (senza i thread del kernel):

`systemd-cgtop -P`
