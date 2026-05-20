# vncviewer

> Avvia un client VNC (Virtual Network Computing).
> Maggiori informazioni: <https://manned.org/vncviewer>.

- Avvia un client VNC che si connette a un host su un dato display:

`vncviewer {{host}}:{{numero_display}}`

- Avvia in modalità a schermo intero:

`vncviewer -FullScreen {{host}}:{{numero_display}}`

- Avvia un client VNC con geometria dello schermo specifica:

`vncviewer --geometry {{larghezza}}x{{altezza}} {{host}}:{{numero_display}}`

- Avvia un client VNC che si connette a un host su una porta specifica:

`vncviewer {{host}}::{{porta}}`
