# ipset

> Crea insiemi IP per regole firewall.
> Maggiori informazioni: <https://manned.org/ipset>.

- Crea un insieme IP vuoto che conterrà indirizzi IP:

`ipset create {{set_name}} hash:ip`

- Distrugge un insieme IP specifico:

`ipset destroy {{set_name}}`

- Aggiunge un indirizzo IP a un insieme specifico:

`ipset add {{set_name}} {{192.168.1.25}}`

- Elimina un indirizzo IP specifico da un insieme:

`ipset del {{set_name}} {{192.168.1.25}}`

- Salva un insieme IP:

`ipset save {{set_name}} > {{path/to/ip_set}}`
