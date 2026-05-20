# avahi-resolve

> Traduce tra nomi host e indirizzi IP.
> Maggiori informazioni: <https://manned.org/avahi-resolve>.

- Risolve un servizio locale nel suo IPv4:

`avahi-resolve -4 {{[-n|--name]}} {{service.local}}`

- Risolve un indirizzo IP in un nome host, in modo verboso:

`avahi-resolve {{[-v|--verbose]}} {{[-a|--address]}} {{IP}}`
