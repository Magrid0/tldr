# reboot

> Riavvia il sistema.
> Maggiori informazioni: <https://manned.org/reboot.8>.

- Riavvia il sistema:

`reboot`

- Spegne il sistema (come `poweroff`):

`reboot {{[-p|--poweroff]}}`

- Arresta (termina tutti i processi e spegne la CPU) il sistema (come `halt`):

`reboot --halt`

- Riavvia immediatamente senza contattare il system manager:

`reboot {{[-f|--force]}}`

- Scrive la voce di spegnimento wtmp senza riavviare il sistema:

`reboot {{[-w|--wtmp-only]}}`
