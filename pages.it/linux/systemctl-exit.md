# systemctl exit

> Chiede al gestore dei servizi di terminare.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#exit%20EXIT_CODE>.

- Esce dal gestore dei servizi utente:

`systemctl exit --user`

- Esce dal gestore dei servizi utente con un codice di uscita specifico:

`systemctl exit {{codice}} --user`

- Chiede al gestore dei servizi del container di uscire (equivalente di `systemctl poweroff` se non in un container):

`systemctl exit`
