# sreport

> Genera report su job, utenti e cluster dai dati di contabilità.
> Maggiori informazioni: <https://slurm.schedmd.com/sreport.html>.

- Mostra i dati di utilizzo del cluster delimitati da pipe:

`sreport {{[-p|--parsable]}} cluster utilization`

- Mostra il numero di job eseguiti:

`sreport job sizes printjobcount`

- Mostra gli utenti con il maggior tempo di CPU utilizzato:

`sreport user topuser`
