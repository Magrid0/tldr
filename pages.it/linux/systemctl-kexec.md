# systemctl kexec

> Riavvia il sistema tramite kexec.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#kexec>.

- Riavvio rapido usando kexec (se il kernel è precaricato):

`systemctl kexec`

- Forza un riavvio normale anche se kexec è disponibile:

`systemctl kexec {{[-f|--force]}}`
