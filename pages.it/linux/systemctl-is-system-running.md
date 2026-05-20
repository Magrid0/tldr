# systemctl is-system-running

> Controlla lo stato corrente del sistema.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#is-system-running>.

- Controlla se il sistema è operativo e stampa lo stato corrente:

`systemctl is-system-running`

- Controlla e stampa lo stato corrente in modo silenzioso (nessun output, solo stato di uscita):

`systemctl is-system-running {{[-q|--quiet]}}`

- Aspetta che il processo di avvio sia completato prima di stampare lo stato corrente:

`systemctl is-system-running --wait`
