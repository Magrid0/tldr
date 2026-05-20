# unshare

> Esegue un comando in nuovi namespace definiti dall'utente.
> Maggiori informazioni: <https://manned.org/unshare>.

- Esegue la shell predefinita:

`unshare`

- Esegue un comando senza condividere l'accesso alle reti connesse:

`sudo unshare {{[-n|--net]}} {{comando}} {{argomento1 argomento2 ...}}`

- Esegue un comando come processo figlio senza condividere mount, processi o reti:

`sudo unshare {{[-minf|--mount --pid --net --fork]}} {{comando}} {{argomento1 argomento2 ...}}`
