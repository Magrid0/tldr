# cec-client

> Gestisce le connessioni CEC del bus seriale.
> Vedi anche: `cec-ctl`.
> Maggiori informazioni: <https://manned.org/cec-client>.

- Elenca tutti gli adattatori CEC:

`cec-client {{[-l|--list-devices]}}`

- Avvia una sessione CEC interattiva:

`sudo cec-client`

- Imposta il nome visualizzato su schermo:

`sudo cec-client {{[-o|--osd-name]}} {{name}}`

- Invia un singolo comando:

`echo {{on 0}} | sudo cec-client {{[-s|--single-command]}}`

- Imposta un dispositivo in standby in modalità interattiva:

`standby {{0}}`

- Accende un dispositivo in modalità interattiva:

`on {{0}}`
