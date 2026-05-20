# systemctl hibernate

> Ibernazione del sistema salvando lo stato corrente su disco e spegnendo.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#hibernate>.

- Iberna il sistema immediatamente:

`systemctl hibernate`

- Forza l'ibernazione anche se sono presenti inibitori:

`systemctl hibernate {{[-f|--force]}}`

- Iberna il sistema senza inviare un messaggio agli utenti connessi:

`systemctl hibernate --no-wall`
