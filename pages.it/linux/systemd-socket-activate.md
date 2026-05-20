# systemd-socket-activate

> Attivazione socket per i servizi systemd.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-socket-activate.html>.

- Attiva un servizio quando un socket specifico viene connesso:

`systemd-socket-activate {{percorso/del/servizio.socket}}`

- Attiva più socket per un servizio:

`systemd-socket-activate {{percorso/del/socket1.service}} {{percorso/del/socket2.service}}`

- Passa variabili d'ambiente al servizio in fase di attivazione:

`{{SYSTEMD_SOCKET_ACTIVATION=1}} systemd-socket-activate {{percorso/del/servizio.socket}}`

- Attiva un servizio insieme a un socket di notifica:

`systemd-socket-activate {{percorso/del/socket.socket}} {{percorso/del/servizio.service}}`

- Attiva un servizio con una porta specificata:

`systemd-socket-activate {{percorso/del/servizio.socket}} {{[-l|--listen]}} {{8080}}`
