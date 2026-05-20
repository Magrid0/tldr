# dstat

> Strumento versatile per generare statistiche sulle risorse di sistema.
> Nota: dstat è deprecato e non più mantenuto.
> Maggiori informazioni: <https://github.com/dstat-real/dstat>.

- Mostra le statistiche di CPU, disco, rete, paging e sistema:

`dstat`

- Mostra le statistiche ogni 5 secondi e solo 4 aggiornamenti:

`dstat {{5}} {{4}}`

- Mostra solo le statistiche di CPU e memoria:

`dstat {{[-c|--cpu]}} {{[-m|--mem]}}`

- Elenca tutti i plugin dstat disponibili:

`dstat --list`

- Mostra il processo che usa più memoria e più CPU:

`dstat --top-mem --top-cpu`

- Mostra la percentuale della batteria e il tempo rimanente:

`dstat --battery --battery-remain`
