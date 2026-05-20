# cgexec

> Limita, misura e controlla le risorse utilizzate dai processi.
> Esistono più tipi di cgroup (detti anche controller), come `cpu`, `memory`, ecc.
> Maggiori informazioni: <https://manned.org/cgexec>.

- Esegue un processo in un dato c[g]ruppo con un dato controller:

`cgexec -g {{controller}}:{{cgroup_name}} {{process_name}}`
