# ip neighbour

> Sottocomando IP per la gestione delle tabelle Neighbour/ARP/NDP.
> Maggiori informazioni: <https://manned.org/ip-neighbour>.

- Mostra le voci della tabella neighbour/ARP:

`ip {{[n|neighbour]}}`

- Rimuove le voci nella tabella neighbour sul dispositivo `ethX`:

`sudo ip {{[n|neighbour]}} {{[f|flush]}} dev {{ethX}}`

- Esegue una ricerca neighbour e restituisce una voce neighbour:

`ip {{[n|neighbour]}} {{[g|get]}} {{lookup_ip}} dev {{ethX}}`

- Aggiunge o elimina una voce ARP per l'indirizzo IP neighbour su `ethX`:

`sudo ip {{[n|neighbour]}} {{add|delete}} {{ip_address}} lladdr {{mac_address}} dev {{ethX}} nud reachable`

- Modifica o sostituisce una voce ARP per l'indirizzo IP neighbour su `ethX`:

`sudo ip {{[n|neighbour]}} {{change|replace}} {{ip_address}} lladdr {{new_mac_address}} dev {{ethX}}`

- Mostra solo neighbour IPv6 o IPv4:

`ip {{-6|-4}} {{[n|neighbour]}}`
