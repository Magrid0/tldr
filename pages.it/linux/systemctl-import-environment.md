# systemctl import-environment

> Importa variabili d'ambiente dalla shell nell'ambiente di systemd.
> Vedi anche: `systemctl show-environment`, `systemctl unset-environment`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#import-environment%20VARIABLE%E2%80%A6>.

- Importa una variabile:

`systemctl import-environment {{variabile}}`

- Importa più variabili:

`systemctl import-environment {{variabile_1 variabile_2 ...}}`

- Importa variabili per servizi utente:

`systemctl import-environment {{variabile}} --user`
