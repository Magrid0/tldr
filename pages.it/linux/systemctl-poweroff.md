# systemctl-poweroff

> Spegne il sistema.
> Vedi anche: `poweroff`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#poweroff>.

- Spegne il sistema:

`systemctl poweroff`

- Spegne il sistema immediatamente senza chiedere ai servizi di fermarsi gentilmente:

`systemctl poweroff {{[-f|--force]}}`

- Spegne il sistema immediatamente senza inviare notifiche agli utenti connessi:

`systemctl poweroff {{[-f|--force]}} --no-wall`
