# sshare

> Elenca le quote delle associazioni a un cluster.
> Maggiori informazioni: <https://slurm.schedmd.com/sshare.html>.

- Elenca le informazioni sulle quote Slurm:

`sshare`

- Controlla il formato di output:

`sshare --{{parsable|parsable2|json|yaml}}`

- Controlla i campi da mostrare:

`sshare {{[-o|--format]}} {{stringa_formato}}`

- Mostra informazioni solo per gli utenti specificati:

`sshare {{[-u|--users]}} {{id_utente_1,id_utente_2,...}}`
