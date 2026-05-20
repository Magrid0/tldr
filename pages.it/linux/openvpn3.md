# openvpn3

> Client OpenVPN 3 per Linux.
> Maggiori informazioni: <https://community.openvpn.net/openvpn/wiki/OpenVPN3Linux>.

- Avvia una nuova sessione VPN:

`openvpn3 session-start {{[-c|--config]}} {{percorso/della/config.conf}}`

- Elenca le sessioni stabilite:

`openvpn3 sessions-list`

- Disconnette la sessione corrente avviata con la configurazione data:

`openvpn3 session-manage {{[-c|--config]}} {{percorso/della/config.conf}} {{[-D|--disconnect]}}`

- Importa una configurazione VPN:

`openvpn3 config-import {{[-c|--config]}} {{percorso/della/config.conf}}`

- Elenca le configurazioni importate:

`openvpn3 configs-list`
