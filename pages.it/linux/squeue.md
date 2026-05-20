# squeue

> Visualizza i job in coda nello scheduler SLURM.
> Maggiori informazioni: <https://manned.org/squeue>.

- Visualizza la coda:

`squeue`

- Visualizza i job in coda di un utente specifico:

`squeue {{[-u|--user]}} {{nome_utente}}`

- Visualizza la coda e aggiornala ogni 5 secondi:

`squeue {{[-i|--iterate]}} {{5}}`

- Visualizza la coda con gli orari di inizio previsti:

`squeue --start`
