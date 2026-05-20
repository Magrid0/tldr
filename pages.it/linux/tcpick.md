# tcpick

> Strumento di sniffing di pacchetti e analisi del traffico di rete.
> Può catturare e visualizzare connessioni e dati TCP. Può anche monitorare il traffico di rete su un'interfaccia, host o porta.
> Maggiori informazioni: <https://manned.org/tcpick>.

- Cattura il traffico su un'interfaccia, porta e host specifici:

`sudo tcpick {{[-i|--interface]}} {{interfaccia}} {{[-C|--colors]}} -h {{host}} -p {{porta}}`

- Cattura il traffico sulla porta 80 (HTTP) di un host specifico:

`sudo tcpick {{[-i|--interface]}} {{eth0}} {{[-C|--colors]}} -h {{192.168.1.100}} -p {{80}}`

- Mostra aiuto:

`tcpick --help`
