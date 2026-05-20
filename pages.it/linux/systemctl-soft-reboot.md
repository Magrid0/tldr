# systemctl soft-reboot

> Arresta e riavvia lo spazio utente, lasciando il kernel in esecuzione.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#soft-reboot>.

- Esegue un soft reboot immediatamente:

`systemctl soft-reboot`

- Forza un soft reboot:

`systemctl soft-reboot {{[-f|--force]}}`

- Pianifica un soft reboot per un orario specifico:

`systemctl soft-reboot --when "{{timestamp}}"`

- Annulla un soft reboot pianificato:

`systemctl soft-reboot --when cancel`
