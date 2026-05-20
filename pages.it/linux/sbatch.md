# sbatch

> Invia un job batch allo scheduler SLURM.
> Maggiori informazioni: <https://manned.org/sbatch>.

- Invia un job batch:

`sbatch {{percorso/del/job.sh}}`

- Invia un job batch con un nome personalizzato:

`sbatch --job-name={{mio_job}} {{percorso/del/job.sh}}`

- Invia un job batch con un limite di tempo di 30 minuti:

`sbatch --time={{00:30:00}} {{percorso/del/job.sh}}`

- Invia un job e richiede più nodi:

`sbatch --nodes={{3}} {{percorso/del/job.sh}}`
