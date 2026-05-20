# rmmod

> Rimuove moduli dal kernel Linux.
> Vedi anche: `kmod`.
> Maggiori informazioni: <https://manned.org/rmmod>.

- Rimuove un modulo dal kernel:

`sudo rmmod {{module_name}}`

- Rimuove un modulo dal kernel e mostra informazioni verbose:

`sudo rmmod --verbose {{module_name}}`

- Rimuove un modulo dal kernel e invia errori a syslog invece di `stderr`:

`sudo rmmod --syslog {{module_name}}`

- Mostra aiuto:

`rmmod --help`

- Mostra versione:

`rmmod --version`
