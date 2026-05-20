# usbip

> Utilizza dispositivi USB da remoto.
> Maggiori informazioni: <https://manned.org/usbip>.

- Elenca tutti i dispositivi USB locali e i loro ID bus:

`usbip list {{[-l|--local]}}`

- Avvia un demone `usbip` sul server:

`systemctl start usbipd`

- Associa un dispositivo USB a `usbip` sul server:

`sudo usbip bind {{[-b|--busid]}} {{bus_id}}`

- Carica il modulo del kernel richiesto da `usbip` sul client:

`sudo modprobe vhci-hcd`

- Collega il dispositivo `usbip` sul client (il bus ID è lo stesso del server):

`sudo usbip attach {{[-r|--remote]}} {{indirizzo_ip}} {{[-b|--busid]}} {{bus_id}}`

- Elenca i dispositivi collegati:

`usbip port`

- Scollega un dispositivo:

`sudo usbip detach {{[-p|--port]}} {{porta}}`

- Sciogli l'associazione di un dispositivo:

`usbip unbind {{[-b|--busid]}} {{bus_id}}`
