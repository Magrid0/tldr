# systemctl suspend

> Sospende il sistema.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#suspend>.

- Sospende il sistema immediatamente:

`systemctl suspend`

- Pianifica una sospensione dopo un ritardo di 5 minuti:

`sleep 300 && systemctl suspend`

- Sospende il sistema e poi lo iberna dopo un ritardo:

`systemctl hybrid-sleep`
