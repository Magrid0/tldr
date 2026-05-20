# qsub

> Invia uno script al sistema di gestione delle code TORQUE.
> Maggiori informazioni: <https://manned.org/qsub.1>.

- Invia uno script con impostazioni predefinite (dipende dalle impostazioni TORQUE):

`qsub {{script.sh}}`

- Invia uno script con un limite di tempo di esecuzione specificato di 1 ora, 2 minuti e 3 secondi:

`qsub -l walltime={{1}}:{{2}}:{{3}} {{script.sh}}`

- Invia uno script che viene eseguito su 2 nodi usando 4 core per nodo:

`qsub -l nodes={{2}}:ppn={{4}} {{script.sh}}`

- Invia uno script a una coda specifica. Nota che diverse code possono avere limiti di tempo massimi e minimi diversi:

`qsub -q {{queue_name}} {{script.sh}}`
