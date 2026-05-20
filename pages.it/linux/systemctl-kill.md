# systemctl kill

> Invia un segnale a uno o più processi di un'unità.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#kill%20PATTERN%E2%80%A6>.

- Invia il segnale `SIGTERM` a un'unità per terminarla:

`systemctl kill {{unità}}`

- Invia un segnale specifico a un'unità:

`systemctl kill {{[-s|--signal]}} {{numero_segnale|nome_segnale}} {{unità}}`

- Invia un segnale `SIGHUP` solo al processo principale di un'unità:

`systemctl kill {{[-s|--signal]}} SIGHUP --kill-whom main {{unità}}`

- Elenca tutti i segnali disponibili:

`systemctl kill {{[-s|--signal]}} help`
