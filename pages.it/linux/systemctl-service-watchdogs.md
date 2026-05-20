# systemctl service-watchdogs

> Ottiene o imposta lo stato globale dei watchdog runtime dei servizi.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#service-watchdogs%20%5Byes%7Cno%5D>.

- Mostra se i watchdog dei servizi sono attualmente abilitati:

`systemctl service-watchdogs`

- Abilita i watchdog runtime dei servizi:

`systemctl service-watchdogs yes`

- Disabilita i watchdog runtime dei servizi:

`systemctl service-watchdogs no`
