# systemctl suspend-then-hibernate

> Sospende il sistema, poi lo iberna automaticamente dopo un periodo di inattività.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#suspend-then-hibernate>.

- Sospende il sistema e lo iberna dopo il ritardo configurato:

`systemctl suspend-then-hibernate`

- Forza sospensione-ibernazione (ignora i blocchi degli inibitori):

`systemctl suspend-then-hibernate {{[-f|--force]}}`
