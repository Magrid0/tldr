# systemctl unset-environment

> Rimuove una o più variabili d'ambiente del gestore dei servizi.
> Annulla l'effetto di `systemctl set-environment`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#unset-environment%20VARIABLE%E2%80%A6>.

- Rimuove una singola variabile d'ambiente:

`systemctl unset-environment {{var}}`

- Rimuove più variabili d'ambiente contemporaneamente:

`systemctl unset-environment {{var1 var2 ...}}`

- Rimuove una variabile d'ambiente dal gestore dei servizi utente:

`systemctl unset-environment {{var}} --user`
