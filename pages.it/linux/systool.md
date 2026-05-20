# systool

> Visualizza le informazioni sui dispositivi di sistema per bus e classi.
> Questo comando fa parte del pacchetto `sysfs`.
> Maggiori informazioni: <https://manned.org/systool>.

- Elenca tutti gli attributi dei dispositivi di un bus (es. `pci`, `usb`). Visualizza tutti i bus usando `ls /sys/bus`:

`systool -b {{bus}} -v`

- Elenca tutti gli attributi di una classe di dispositivi (es. `drm`, `block`). Visualizza tutte le classi usando `ls /sys/class`:

`systool -c {{classe}} -v`

- Mostra solo i driver dei dispositivi di un bus (es. `pci`, `usb`):

`systool -b {{bus}} -D`
