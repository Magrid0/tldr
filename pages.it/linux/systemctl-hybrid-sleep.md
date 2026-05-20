# systemctl hybrid-sleep

> Mette il sistema in sospensione ibrida, che combina sospensione in RAM e ibernazione.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#hybrid-sleep>.

- Mette il sistema in sospensione ibrida immediatamente:

`systemctl hybrid-sleep`

- Forza la sospensione ibrida anche se sono presenti inibitori:

`systemctl hybrid-sleep {{[-f|--force]}}`

- Mette il sistema in sospensione ibrida senza inviare un messaggio wall agli utenti connessi:

`systemctl hybrid-sleep --no-wall`
