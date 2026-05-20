# daemonize

> Esegue un comando (che non si demonizza da solo) come demone Unix.
> Maggiori informazioni: <https://software.clapper.org/daemonize/>.

- Esegue un comando come demone:

`daemonize {{command}} {{command_arguments}}`

- Scrive il PID nel file specificato:

`daemonize -p {{path/to/pidfile}} {{command}} {{command_arguments}}`

- Usa un file di lock per garantire che una sola istanza sia eseguita alla volta:

`daemonize -l {{path/to/lockfile}} {{command}} {{command_arguments}}`

- Usa l'account utente specificato:

`sudo daemonize -u {{user}} {{command}} {{command_arguments}}`
