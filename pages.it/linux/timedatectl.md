# timedatectl

> Controlla l'ora e la data di sistema.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/timedatectl.html>.

- Controlla l'ora corrente dell'orologio di sistema:

`timedatectl`

- Imposta direttamente l'ora locale dell'orologio di sistema:

`timedatectl set-time "{{yyyy-MM-dd hh:mm:ss}}"`

- Elenca i fusi orari disponibili:

`timedatectl list-timezones`

- Imposta il fuso orario di sistema:

`timedatectl set-timezone {{fuso_orario}}`

- Abilita la sincronizzazione NTP (Network Time Protocol):

`timedatectl set-ntp on`

- Mostra informazioni sulla sincronizzazione dell'ora (disponibile solo quando si utilizza `systemd-timesyncd`):

`timedatectl timesync-status`

- Cambia lo standard dell'ora dell'orologio hardware in ora locale:

`timedatectl set-local-rtc 1`
