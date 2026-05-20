# cfdisk

> Gestisce le tabelle delle partizioni e le partizioni su un disco rigido utilizzando un'interfaccia curses.
> Vedi anche: `parted`.
> Maggiori informazioni: <https://manned.org/cfdisk>.

- Avvia il manipolatore di partizioni con un dispositivo specifico:

`sudo cfdisk {{/dev/sdX}}`

- Crea una nuova tabella delle partizioni per un dispositivo specifico e la gestisce:

`sudo cfdisk {{[-z|--zero]}} {{/dev/sdX}}`
