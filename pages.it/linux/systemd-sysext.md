# systemd-sysext

> Attiva o disattiva le immagini di estensione del sistema.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-sysext.html>.

- Elenca le immagini di estensione installate:

`systemd-sysext list`

- Unisce le immagini di estensione del sistema in `/usr/` e `/opt/`:

`systemd-sysext merge`

- Controlla lo stato corrente dell'unione:

`systemd-sysext`

- Separa tutte le immagini di estensione del sistema attualmente installate da `/usr/` e `/opt/`:

`systemd-sysext unmerge`

- Aggiorna le immagini di estensione del sistema (una combinazione di `unmerge` e `merge`):

`systemd-sysext refresh`
