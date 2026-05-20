# sacct

> Mostra i dati di contabilità del servizio Slurm.
> Maggiori informazioni: <https://slurm.schedmd.com/sacct.html>.

- Mostra ID job, nome job, partizione, account, numero di CPU allocate, stato del job e codici di uscita per i job recenti:

`sacct`

- Mostra ID job, stato del job e codice di uscita per i job recenti:

`sacct {{[-b|--brief]}}`

- Mostra le allocazioni di un job:

`sacct {{[-j|--jobs]}} {{job_id}} {{[-X|--allocations]}}`

- Mostra tempo trascorso, nome job, numero di CPU richieste e memoria richiesta di un job:

`sacct {{[-j|--jobs]}} {{job_id}} {{[-o|--format]}} Elapsed,JobName,ReqCPUS,ReqMem`

- Mostra i job recenti che si sono verificati da una settimana fa fino al giorno presente:

`sacct {{[-S|--starttime]}} $(date {{[-d|--date]}} "1 week ago" +'%F')`

- Mostra un numero maggiore di caratteri per un attributo:

`sacct {{[-o|--format]}} JobID,JobName%100`
