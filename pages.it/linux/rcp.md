# rcp

> Copia file tra sistemi locali e remoti.
> Emula il comportamento del comando `cp` ma opera su macchine diverse.
> Maggiori informazioni: <https://www.gnu.org/software/inetutils/manual/inetutils.html#rcp-invocation>.

- Copia un file su un host remoto:

`rcp {{path/to/local_file}} {{username}}@{{remote_host}}:/{{path/to/destination}}/`

- Copia una directory in modo ricorsivo:

`rcp {{[-r|--recursive]}} {{path/to/local_directory}} {{username}}@{{remote_host}}:/{{path/to/destination}}/`

- Mantiene gli attributi dei file:

`rcp {{[-p|--preserve]}} {{path/to/local_file}} {{username}}@{{remote_host}}:/{{path/to/destination}}/`

- Forza la copia senza conferma:

`rcp {{[-f|--from]}} {{path/to/local_file}} {{username}}@{{remote_host}}:/{{path/to/destination}}/`
