# slurmctld

> Monitora tutti gli altri demone e risorse Slurm, accetta lavoro (job) e alloca risorse a quei job.
> Maggiori informazioni: <https://slurm.schedmd.com/slurmctld.html>.

- Pulisce tutti gli stati precedenti di `slurmctld` dal suo ultimo checkpoint:

`slurmctld -c`

- Imposta il nice value del demone al valore specificato, tipicamente un numero negativo:

`slurmctld -n {{valore}}`

- Scrive i messaggi di log nel file specificato:

`slurmctld -L {{percorso/del/file_output}}`

- Mostra aiuto:

`slurmctld -h`

- Mostra versione:

`slurmctld -V`
