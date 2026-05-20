# openrc

> Il gestore di servizi OpenRC.
> Vedi anche: `rc-status`, `rc-update`, `rc-service`.
> Maggiori informazioni: <https://wiki.gentoo.org/wiki/OpenRC>.

- Cambia a un runlevel specifico:

`sudo openrc {{nome_runlevel}}`

- Cambia a un runlevel specifico, ma non ferma alcun servizio esistente:

`sudo openrc {{[-n|--no-stop]}} {{nome_runlevel}}`
