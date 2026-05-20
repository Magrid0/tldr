# salloc

> Avvia una sessione interattiva di shell o esegue un comando allocando uno o più nodi in un cluster.
> Maggiori informazioni: <https://slurm.schedmd.com/salloc.html>.

- Avvia una sessione interattiva di shell su un nodo del cluster:

`saloc`

- Esegue il comando specificato in modo sincrono su un nodo del cluster:

`salloc {{ls --all}}`

- Alloca solo i nodi che soddisfano i vincoli specificati:

`salloc {{[-C|--constraint]}} {{(amd|intel)&gpu}}`
