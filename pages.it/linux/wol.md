# wol

> Client per l'invio di pacchetti magici Wake-on-LAN.
> Maggiori informazioni: <https://sourceforge.net/projects/wake-on-lan/>.

- Invia un pacchetto WoL a un dispositivo:

`wol {{indirizzo_mac}}`

- Invia un pacchetto WoL a un dispositivo in un'altra sottorete basato sul suo IP:

`wol {{[-i|--ipaddr]}} {{indirizzo_ip}} {{indirizzo_mac}}`

- Invia un pacchetto WoL a un dispositivo in un'altra sottorete basato sul suo hostname:

`wol {{[-h|--host]}} {{hostname}} {{indirizzo_mac}}`

- Invia un pacchetto WoL a una porta specifica su un host:

`wol {{[-p|--port]}} {{numero_porta}} {{indirizzo_mac}}`

- Leggi indirizzi hardware, indirizzi IP/hostname, porte opzionali e password SecureON da un file:

`wol {{[-f|--file]}} {{percorso/del/file}}`

- Attiva l'output verboso:

`wol {{[-v|--verbose]}} {{indirizzo_mac}}`
