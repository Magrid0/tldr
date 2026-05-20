# waitpid

> Attende la terminazione di processi arbitrari.
> Vedi anche: `wait`.
> Maggiori informazioni: <https://manned.org/waitpid>.

- Dormi finché tutti i processi i cui PID sono stati specificati non sono terminati:

`waitpid {{pid1 pid2 ...}}`

- Dormi per al massimo `n` secondi:

`waitpid {{[-t|--timeout]}} {{n}} {{pid1 pid2 ...}}`

- Non generare errore se i PID specificati sono già terminati:

`waitpid {{[-e|--exited]}} {{pid1 pid2 ...}}`

- Dormi finché `n` dei processi specificati non sono terminati:

`waitpid {{[-c|--count]}} {{n}} {{pid1 pid2 ...}}`

- Mostra aiuto:

`waitpid {{[-h|--help]}}`
