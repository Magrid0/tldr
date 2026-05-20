# numactl

> Controlla la politica NUMA per processi o memoria condivisa.
> Maggiori informazioni: <https://manned.org/numactl>.

- Esegue un comando sul nodo 0 con memoria allocata sui nodi 0 e 1:

`numactl --cpunodebind={{0}} --membind={{0,1}} -- {{comando}} {{argomenti_comando}}`

- Esegue un comando sulle CPU (core) 0-4 e 8-12 del cpuset corrente:

`numactl --physcpubind={{+0-4,8-12}} -- {{comando}} {{argomenti_comando}}`

- Esegue un comando con la sua memoria interlacciata su tutte le CPU:

`numactl --interleave={{all}} -- {{comando}} {{argomenti_comando}}`
