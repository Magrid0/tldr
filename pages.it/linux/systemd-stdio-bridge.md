# systemd-stdio-bridge

> Implementa un proxy tra `stdin`/`stdout` e un D-Bus.
> Nota: si aspetta di ricevere una connessione aperta tramite `stdin`/`stdout` all'avvio e creerà una nuova connessione al bus specificato.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-stdio-bridge.html>.

- Inoltra `stdin`/`stdout` al bus di sistema locale:

`systemd-stdio-bridge`

- Inoltra `stdin`/`stdout` al D-Bus di un utente specifico:

`systemd-stdio-bridge --{{user}}`

- Inoltra `stdin`/`stdout` al bus di sistema locale all'interno di un contenitore specifico:

`systemd-stdio-bridge {{[-M|--machine]}} {{mio_contenitore}}`

- Inoltra `stdin`/`stdout` a un indirizzo D-Bus personalizzato:

`systemd-stdio-bridge {{[-p|--bus-path]}} unix:path=/{{percorso/del/socket_dbus}}`
