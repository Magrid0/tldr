# inxi

> Stampa un riepilogo delle informazioni di sistema e delle risorse per scopi di debug.
> Vedi anche: `lshw`, `hwinfo`, `dmidecode`.
> Maggiori informazioni: <https://manned.org/inxi>.

- Stampa un riepilogo delle informazioni su CPU, memoria, hard disk e kernel:

`inxi`

- Stampa una descrizione completa delle informazioni su CPU, memoria, disco, rete e processi e filtra le informazioni sensibili:

`inxi {{[-ez|--expanded --filter]}}`

- Stampa un riepilogo delle informazioni sulla CPU:

`inxi {{[-C|--cpu]}}`

- Stampa un riepilogo delle informazioni grafiche:

`inxi {{[-G|--graphics]}}`

- Stampa un riepilogo della RAM di sistema:

`inxi {{[-m|--memory]}}`

- Stampa un riepilogo dell'audio di sistema:

`inxi {{[-A|--audio]}}`

- Stampa i dati dei sensori disponibili:

`inxi {{[-s|--sensors]}}`

- Stampa informazioni sui repository della distribuzione:

`inxi {{[-r|--repos]}}`
