# systemctl set-environment

> Imposta una o più variabili d'ambiente del gestore dei servizi.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#set-environment%20VARIABLE=VALUE%E2%80%A6>.

- Imposta una singola variabile d'ambiente:

`systemctl set-environment {{var valore}}`

- Imposta più variabili d'ambiente contemporaneamente:

`systemctl set-environment {{var1 valore1 var2 valore2 ...}}`

- Imposta una variabile d'ambiente per il gestore dei servizi utente:

`systemctl set-environment {{var valore}} --user`
