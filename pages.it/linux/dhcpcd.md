# dhcpcd

> Client DHCP.
> Maggiori informazioni: <https://roy.marples.name/projects/dhcpcd>.

- Rilascia tutti i lease degli indirizzi:

`sudo dhcpcd {{[-k|--release]}}`

- Richiede nuovi lease al server DHCP:

`sudo dhcpcd {{[-n|--rebind]}}`

- Stampa l'ultimo lease acquisito per una data interfaccia:

`sudo dhcpcd {{[-U|--dumplease]}} {{interface_name}}`

- Stampa l'ultimo lease acquisito per tutte le interfacce:

`sudo dhcpcd {{[-U|--dumplease]}}`
