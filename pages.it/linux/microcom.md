# microcom

> Un programma terminale minimalista, usato per accedere a dispositivi remoti tramite una connessione seriale, CAN o telnet dalla console.
> Maggiori informazioni: <https://manned.org/microcom>.

- Apre una porta seriale usando il baud rate specificato:

`microcom {{[-p|--port]}} {{/dev/ttyXYZ}} {{[-s|--speed]}} {{baud_rate}}`

- Stabilisce una connessione telnet all'host specificato:

`microcom {{[-t|--telnet]}} {{hostname}}:{{port}}`
