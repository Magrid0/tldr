# flock

> Gestisce i blocchi dei file dagli script di shell.
> Può essere utilizzato per garantire che sia in esecuzione una sola istanza di un comando.
> Maggiori informazioni: <https://manned.org/flock>.

- Esegue un comando con un blocco file non appena il blocco è disponibile:

`flock {{path/to/lock.lock}} {{command}}`

- Esegue un comando con un blocco file, o esce se il blocco è attualmente mantenuto (con codice di uscita 1):

`flock {{[-n|--nonblock]}} {{path/to/lock.lock}} {{command}}`

- Esegue un comando con un blocco file, o esce con un codice di errore specifico se il blocco è attualmente mantenuto:

`flock {{[-n|--nonblock]}} {{[-E|--conflict-exit-code]}} {{123}} {{path/to/lock.lock}} {{command}}`

- Esegue un comando con un blocco file, aspettando fino a 10 secondi che il blocco sia disponibile prima di arrendersi:

`flock {{[-w|--timeout]}} 10 {{path/to/lock.lock}} {{command}}`

- Esegue il backup di un gruppo di file, aspettando che il precedente comando `tar` finisca se è ancora in esecuzione altrove e mantiene lo stesso blocco file (può essere utilizzato in un job `cron` eseguito frequentemente):

`flock {{path/to/backup.lock}} {{tar -cvf path/to/backup.tar path/to/data/}}`
