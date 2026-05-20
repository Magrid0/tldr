# systemctl reenable

> Riabilita una o più unità.
> Usato quando cambiano i target di un servizio.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#reenable%20UNIT%E2%80%A6>.

- Riabilita un'unità, ripristinando i suoi symlink predefiniti:

`systemctl reenable {{unità}}`

- Riabilita più unità contemporaneamente:

`systemctl reenable {{unità1 unità2 ...}}`

- Riabilita un'unità e la avvia immediatamente:

`systemctl reenable {{unità}} --now`
