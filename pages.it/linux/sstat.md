# sstat

> Visualizza informazioni sui job in esecuzione.
> Maggiori informazioni: <https://slurm.schedmd.com/sstat.html>.

- Mostra le informazioni sullo stato di un elenco separato da virgole di job:

`sstat {{[-j|--jobs]}} {{id_job}}`

- Mostra ID job, CPU media e dimensione media della memoria virtuale di un elenco separato da virgole di job, con pipe come delimitatori di colonna:

`sstat {{[-p|--parsable]}} {{[-j|--jobs]}} {{id_job}} {{[-o|--format]}} {{JobID,AveCPU,AveVMSize}}`

- Mostra l'elenco dei campi disponibili:

`sstat {{[-e|--helpformat]}}`
