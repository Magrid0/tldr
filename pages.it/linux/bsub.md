# bsub

> Invia job batch allo scheduler LSF (Load Sharing Facility).
> Maggiori informazioni: <https://www.ibm.com/docs/spectrum-lsf/latest?topic=reference-bsub>.

- Invia un file script come job:

`bsub {{path/to/script.sh}}`

- Invia un job a una coda specifica:

`bsub -q {{queue_name}} make all`

- Invia un job con un nome e reindirizza output ed errori:

`bsub -J {{job_name}} --output {{path/to/output.log}} --error {{path/to/error.log}} {{path/to/script.sh}}`

- Richiede 8 core CPU e 16 GB di memoria per un comando:

`bsub -n 8 -M 16G cargo build --release`

- Esegue una shell interattiva nella sessione corrente:

`bsub -I bash`

- Invia un job con un limite di tempo di esecuzione di 45 minuti:

`bsub -W 45 {{path/to/script.sh}}`
