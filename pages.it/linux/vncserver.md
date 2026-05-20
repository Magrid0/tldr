# vncserver

> Avvia un desktop VNC (Virtual Network Computing).
> Maggiori informazioni: <https://manned.org/vncserver.1x>.

- Avvia un server VNC sul prossimo display disponibile:

`vncserver`

- Avvia un server VNC con geometria dello schermo specifica:

`vncserver --geometry {{larghezza}}x{{altezza}}`

- Termina un'istanza del server VNC in esecuzione su un display specifico:

`vncserver --kill :{{numero_display}}`
