# krdc

> Si connette a un server desktop remoto.
> Maggiori informazioni: <https://invent.kde.org/network/krdc#usage>.

- Avvia KRDC:

`krdc`

- Si connette automaticamente a un host con il nome utente corrente usando VNC:

`krdc {{remote_host}}`

- Specifica il protocollo e il nome utente usati per connettersi a un host:

`krdc {{vnc|rdp}}://{{username}}@{{remote_host}}`

- Avvia la connessione in modalità schermo intero:

`krdc {{rdp://username@ip_address}} --fullscreen`
