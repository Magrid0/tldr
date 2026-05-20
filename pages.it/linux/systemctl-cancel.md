# systemctl cancel

> Annulla uno o più job in sospeso nel gestore di sistema o nel gestore utente.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#cancel%20JOB%E2%80%A6>.

- Annulla un job tramite il suo ID numerico:

`systemctl cancel {{id_job}}`

- Annulla più job:

`systemctl cancel {{id_job1 id_job2 ...}}`

- Annulla tutti i job in sospeso:

`systemctl cancel`

- Annulla un job nel gestore dei servizi utente:

`systemctl cancel {{id_job}} --user`
