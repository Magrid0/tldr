# run0

> Eleva i privileggi in modo interattivo.
> Simile a `sudo`, ma non è un binario SUID, l'autenticazione avviene tramite polkit e i comandi vengono invocati da un servizio `systemd`.
> Vedi anche: `sudo`, `pkexec`, `doas`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/run0.html>.

- Esegue un comando come root:

`run0 {{command}}`

- Esegue un comando come un altro utente e/o gruppo:

`run0 {{[-u|--user]}} {{username|uid}} {{[-g|--group]}} {{group_name|gid}} {{command}}`
