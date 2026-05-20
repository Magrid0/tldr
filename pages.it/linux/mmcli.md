# mmcli

> Controlla e monitora ModemManager.
> Maggiori informazioni: <https://www.freedesktop.org/software/ModemManager/man/latest/mmcli.1.html>.

- Elenca i modem disponibili:

`mmcli --list-modems`

- Stampa informazioni su un modem:

`mmcli --modem={{modem}}`

- Abilita un modem:

`mmcli --modem={{modem}} --enable`

- Elenca i messaggi SMS disponibili sul modem:

`sudo mmcli --modem={{modem}} --messaging-list-sms`

- Elimina un messaggio dal modem, specificandone il percorso:

`sudo mmcli --modem={{modem}} --messaging-delete-sms={{path/to/message_file}}`
