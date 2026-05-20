# daemon

> Trasforma altri processi in demoni.
> Maggiori informazioni: <https://manned.org/daemon.1>.

- Esegue un comando come demone:

`daemon {{[-n|--name]}} "{{name}}" {{command}}`

- Esegue un comando come demone che verrà riavviato se il comando si blocca:

`daemon {{[-n|--name]}} "{{name}}" {{[-r|--respawn]}} {{command}}`

- Esegue un comando come demone che verrà riavviato in caso di crash, con due tentativi ogni 10 secondi:

`daemon {{[-n|--name]}} "{{name}}" {{[-r|--respawn]}} {{[-A|--attempts]}} 2 {{[-L|--delay]}} 10 {{command}}`

- Esegue un comando come demone, scrivendo i log in un file specifico:

`daemon {{[-n|--name]}} "{{name}}" {{[-l|--errlog]}} {{path/to/file.log}} {{command}}`

- Termina un demone (SIGTERM):

`daemon {{[-n|--name]}} "{{name}}" --stop`

- Elenca i demoni:

`daemon --list`
