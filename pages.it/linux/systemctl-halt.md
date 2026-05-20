# systemctl-halt

> Arresta e ferma il sistema (ferma il kernel del sistema operativo ma lascia l'hardware acceso).
> Vedi anche: `halt`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#halt>.

- Ferma il sistema:

`systemctl halt`

- Ferma il sistema immediatamente senza chiedere ai servizi di fermarsi gentilmente:

`systemctl halt {{[-f|--force]}}`

- Ferma il sistema immediatamente senza inviare notifiche agli utenti connessi:

`systemctl halt {{[-f|--force]}} --no-wall`

- Ferma il sistema immediatamente senza terminare alcun processo o smontare filesystem (pericoloso, può causare perdita di dati):

`systemctl halt {{[-ff|--force --force]}}`

- Pianifica un arresto a un orario specifico (es. 23:00):

`systemctl halt --when 23:00`

- Pianifica un arresto dopo un certo intervallo (es. 2 ore):

`systemctl halt --when +2h`

- Annulla un arresto pianificato:

`systemctl halt --when cancel`
