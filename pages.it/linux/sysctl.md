# sysctl

> Elenca e modifica le variabili di runtime del kernel.
> Maggiori informazioni: <https://manned.org/sysctl.8>.

- Mostra tutte le variabili disponibili e i loro valori:

`sysctl {{[-a|--all]}}`

- Imposta una variabile di stato del kernel modificabile:

`sysctl {{[-w|--write]}} {{sezione.parametro}}={{valore}}`

- Ottiene il numero di gestori di file attualmente aperti:

`sysctl fs.file-nr`

- Ottiene il limite per i file aperti simultaneamente:

`sysctl fs.file-max`

- Applica le modifiche da `/etc/sysctl.conf`:

`sysctl {{[-p|--load]}}`
