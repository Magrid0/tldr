# sprio

> Visualizza i fattori che determinano la priorità di scheduling di un job.
> Maggiori informazioni: <https://slurm.schedmd.com/sprio.html>.

- Visualizza i fattori che determinano la priorità di scheduling di tutti i job:

`sprio`

- Visualizza i fattori che determinano la priorità di scheduling del job specificato:

`sprio {{[-j|--jobs]}} {{id_job_1,id_job_2,...}}`

- Mostra informazioni aggiuntive:

`sprio {{[-l|--long]}}`

- Visualizza informazioni per i job di utenti specificati:

`sprio {{[-u|--user]}} {{nome_utente_1,nome_utente_2,...}}`

- Stampa i pesi per ogni fattore che determina la priorità di scheduling:

`sprio {{[-w|--weights]}}`
