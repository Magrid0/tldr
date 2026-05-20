# rc-update

> Aggiunge e rimuove servizi OpenRC dai runlevel.
> Vedi anche: `openrc`.
> Maggiori informazioni: <https://manned.org/rc-update>.

- Elenca i servizi abilitati e i runlevel a cui sono aggiunti:

`rc-update`

- Elenca tutti i servizi:

`rc-update {{[-v|--verbose]}}`

- Aggiunge un servizio a un runlevel:

`sudo rc-update add {{service_name}} {{runlevel}}`

- Elimina un servizio da un runlevel:

`sudo rc-update {{[del|delete]}} {{service_name}} {{runlevel}}`

- Elimina un servizio da tutti i runlevel:

`sudo rc-update {{[-a|--all]}} {{[del|delete]}} {{service_name}}`
