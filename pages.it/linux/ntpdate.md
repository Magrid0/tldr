# ntpdate

> Sincronizza e imposta la data e l'ora tramite NTP.
> Maggiori informazioni: <https://manned.org/ntpdate>.

- Sincronizza e imposta data e ora:

`sudo ntpdate {{host}}`

- Interroga l'host senza impostare l'ora:

`ntpdate -q {{host}}`

- Usa una porta non privilegiata nel caso un firewall stia bloccando le porte privilegiate:

`sudo ntpdate -u {{host}}`

- Forza l'ora a essere impostata usando `settimeofday` invece di `slewed`:

`sudo ntpdate -b {{host}}`
