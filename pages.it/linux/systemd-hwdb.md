# systemd-hwdb

> Strumento di gestione del database hardware.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-hwdb.html>.

- Aggiorna il database hardware binario in `/etc/udev`:

`sudo systemd-hwdb update`

- Interroga il database hardware e stampa il risultato per una modalias specifica:

`systemd-hwdb query {{modalias}}`

- Aggiorna il database hardware binario, restituendo un valore di uscita diverso da zero in caso di errore di analisi:

`sudo systemd-hwdb {{[-s|--strict]}} update`

- Aggiorna il database hardware binario in `/usr/lib/udev`:

`sudo systemd-hwdb --usr update`

- Aggiorna il database hardware binario nel percorso root specificato:

`systemd-hwdb {{[-r|--root]}} {{percorso/della/root}} update`
