# sattach

> Si collega a uno step di un job Slurm.
> Maggiori informazioni: <https://slurm.schedmd.com/sattach.html>.

- Reindirizza i flussi IO (`stdout`, `stderr` e `stdin`) di uno step di un job Slurm al terminale corrente:

`sattach {{id_job}}.{{id_step}}`

- Usa l'input della console corrente come `stdin` per l'attività specificata:

`sattach --input-filter {{numero_attività}}`

- Reindirizza solo `stdin`/`stderr` dell'attività specificata:

`sattach --{{output|error}}-filter {{numero_attività}}`
