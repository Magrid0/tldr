# auditctl

> Utility per controllare il comportamento, ottenere lo stato e gestire le regole del Sistema di Audit Linux.
> Maggiori informazioni: <https://manned.org/auditctl>.

- Mostra lo [s]tato del sistema di audit:

`sudo auditctl -s`

- [l]ista tutte le regole di audit attualmente caricate:

`sudo auditctl -l`

- [D]elete tutte le regole di audit:

`sudo auditctl -D`

- [e]nable/disabilita il sistema di audit:

`sudo auditctl -e {{1|0}}`

- Monitora un file per modifiche:

`sudo auditctl -a always,exit -F arch=b64 -F path=/{{path/to/file}} -F perm=wa`

- Monitora ricorsivamente una directory per modifiche:

`sudo auditctl -a always,exit -F arch=b64 -F dir=/{{path/to/directory}}/ -F perm=wa`

- Mostra [h]elp:

`auditctl -h`
