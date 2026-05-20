# slurmrestd

> Interfaccia a Slurm via API REST.
> Nota: può essere usato in due modalità: Modalità Inetd e Modalità Ascolto.
> Maggiori informazioni: <https://slurm.schedmd.com/slurmrestd.html>.

- Cambia l'ID del [g]ruppo (e abbandona i gruppi supplementari) prima di elaborare le richieste del client:

`slurmrestd -g {{id_gruppo}} {{[host]:porta|unix:/percorso/del/socket}}`

- Elenco separato da virgole di plugin di [a]utenticazione da caricare:

`slurmrestd -a {{plugin_autenticazione}} {{[host]:porta|unix:/percorso/del/socket}}`

- Legge la configurazione di Slurm dal [f]ile specificato:

`slurmrestd -f {{percorso/del/file}}`

- Cambia l'ID [u]tente prima di elaborare la richiesta del client:

`slurmrestd -u {{id_utente}}`

- Mostra [a]iuto:

`slurmrestd -h`

- Mostra [v]ersione:

`slurmrestd -V`
