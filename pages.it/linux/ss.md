# ss

> Utilità per investigate sui socket.
> Maggiori informazioni: <https://manned.org/ss>.

- Mostra tutti i socket TCP/UDP/RAW/UNIX:

`ss {{[-a|--all]}} {{--tcp|--udp|--raw|--unix}}`

- Filtra i socket TCP per stati, solo/esclusi:

`ss {{state|exclude}} {{bucket|big|connected|synchronized|...}}`

- Mostra tutti i socket TCP connessi alla porta HTTPS locale (443):

`ss {{[-t|--tcp]}} src :{{443}}`

- Mostra tutti i socket TCP in ascolto sulla porta locale 8080:

`ss {{[-lt|--listening --tcp]}} src :{{8080}}`

- Mostra tutti i socket TCP insieme ai processi connessi a una porta SSH remota:

`ss {{[-pt|--processes --tcp]}} dst :{{ssh}}`

- Mostra tutti i socket UDP connessi su porte di origine e destinazione specifiche:

`ss {{[-u|--udp]}} 'sport == :{{porta_sorgente}} and dport == :{{porta_destinazione}}'`

- Mostra tutti i socket TCP IPv4 connessi localmente sulla sottorete 192.168.0.0/16:

`ss {{[-4t|--ipv4 --tcp]}} src {{192.168/16}}`

- Termina una connessione socket IPv4 o IPv6 con un IP e una porta di destinazione specifici:

`ss {{[-K|--kill]}} dst {{indirizzo_ip}} dport = {{porta}}`
