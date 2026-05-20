# xfreerdp

> Implementazione del protocollo Remote Desktop libero.
> Maggiori informazioni: <https://github.com/FreeRDP/FreeRDP/wiki/CommandLineInterface-(possibly-not-up-to-date,-check-application-help-text-for-most-up-to-date-version)>.

- Connettiti a un server FreeRDP:

`xfreerdp /u:{{nome_utente}} /p:{{password}} /v:{{indirizzo_ip}}`

- Connettiti a un server FreeRDP e attiva il reindirizzamento dell'output audio usando il dispositivo `sys:alsa`:

`xfreerdp /u:{{nome_utente}} /p:{{password}} /v:{{indirizzo_ip}} /sound:{{sys:alsa}}`

- Connettiti a un server FreeRDP con risoluzione dinamica:

`xfreerdp /v:{{indirizzo_ip}} /u:{{nome_utente}} /p:{{password}} /dynamic-resolution`

- Connettiti a un server FreeRDP con reindirizzamento degli appunti:

`xfreerdp /v:{{indirizzo_ip}} /u:{{nome_utente}} /p:{{password}} +clipboard`

- Connettiti a un server FreeRDP ignorando qualsiasi controllo del certificato:

`xfreerdp /v:{{indirizzo_ip}} /u:{{nome_utente}} /p:{{password}} /cert:ignore`

- Connettiti a un server FreeRDP con una directory condivisa:

`xfreerdp /v:{{indirizzo_ip}} /u:{{nome_utente}} /p:{{password}} /drive:{{path/to/directory}},{{nome_condivisione}}`
