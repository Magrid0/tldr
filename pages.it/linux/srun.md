# srun

> Crea un job interattivo slurm o si connette a un job esistente.
> Maggiori informazioni: <https://slurm.schedmd.com/srun.html>.

- Invia un job interattivo base:

`srun --pty /bin/bash`

- Invia un job interattivo con attributi differenti:

`srun --ntasks-per-node {{num_cores}} --mem-per-cpu {{memoria_MB}} --pty /bin/bash`

- Si connette a un nodo worker con un job in esecuzione:

`srun --jobid {{id_job}} --pty /bin/bash`
