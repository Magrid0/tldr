# scontrol

> Mostra informazioni sui job e li modifica.
> Maggiori informazioni: <https://slurm.schedmd.com/scontrol.html>.

- Mostra informazioni per un job:

`scontrol show job {{id_job}}`

- Sospende un elenco separato da virgole di job in esecuzione:

`scontrol suspend {{id_job1,id_job2,...}}`

- Riprende un elenco separato da virgole di job sospesi:

`scontrol resume {{id_job1,id_job2,...}}`

- Mette in attesa un elenco separato da virgole di job in coda (usa il comando `release` per permettere la pianificazione dei job):

`scontrol hold {{id_job1,id_job2,...}}`

- Rilascia un elenco separato da virgole di job sospesi:

`scontrol release {{id_job1,id_job2,...}}`
