# systemctl whoami

> Mostra le unità a cui appartengono i processi.
> Se non viene specificato alcun PID, mostra l'unità in cui viene invocato il comando `systemctl` stesso.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#whoami%20%5BPID%E2%80%A6%5D>.

- Mostra l'unità della shell corrente (dove è in esecuzione `systemctl`):

`systemctl whoami`

- Mostra l'unità della shell corrente nel gestore dei servizi utente (servizi gestiti per la sessione di login):

`systemctl whoami --user`

- Mostra l'unità a cui appartiene un processo specifico:

`systemctl whoami {{pid}}`

- Mostra le unità per più processi:

`systemctl whoami {{pid1 pid2 ...}}`
