# udevadm

> Strumento di gestione Linux `udev`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/udevadm.html>.

- Monitora tutti gli eventi dei dispositivi:

`sudo udevadm monitor`

- Stampa gli `uevents` inviati dal kernel:

`sudo udevadm monitor {{[-k|--kernel]}}`

- Stampa gli eventi dei dispositivi dopo essere stati elaborati da `udev`:

`sudo udevadm monitor {{[-u|--udev]}}`

- Elenca gli attributi del dispositivo `/dev/sda`:

`sudo udevadm info {{[-a|--attribute-walk]}} {{/dev/sda}}`

- Ricarica tutte le regole di `udev`:

`sudo udevadm control {{[-R|--reload]}}`

- Attiva l'esecuzione di tutte le regole `udev`:

`sudo udevadm trigger`

- Testa un evento simulando il caricamento di `/dev/sda`:

`sudo udevadm test {{/dev/sda}}`
