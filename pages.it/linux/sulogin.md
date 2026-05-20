# sulogin

> Effettua il login come root durante la modalità a utente singolo.
> Maggiori informazioni: <https://manned.org/sulogin>.

- Avvia `sulogin` sulla console predefinita:

`sudo sulogin`

- Avvia `sulogin` su un dispositivo TTY specifico:

`sudo sulogin {{/dev/ttyX}}`

- Imposta un timeout massimo (in secondi) per l'inserimento della password di root prima di continuare l'avvio normale:

`sudo sulogin {{[-t|--timeout]}} {{timeout}}`

- Avvia la shell di root come shell di login:

`sudo sulogin {{[-p|--login-shell]}}`

- Forza una shell di root senza chiedere una password quando i metodi predefiniti per ottenere la password falliscono:

`sudo sulogin {{[-e|--force]}}`
