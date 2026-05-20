# gpclient

> Si connette a una VPN GlobalProtect su Linux tramite OpenConnect.
> Maggiori informazioni: <https://github.com/yuezk/GlobalProtect-openconnect>.

- Si connette a una VPN GlobalProtect usando un server portal:

`gpclient connect {{vpn_gateway_url}}`

- Si disconnette dal server VPN attualmente connesso:

`gpclient disconnect`

- Avvia l'interfaccia grafica (GUI) per la gestione della VPN:

`gpclient launch-gui`

- Usa una soluzione alternativa OpenSSL per bypassare errori di rinegoziazione legacy:

`gpclient connect --fix-openssl {{vpn_gateway_url}}`

- Ignora gli errori TLS durante la connessione:

`gpclient connect --ignore-tls-errors {{vpn_gateway_url}}`

- Mostra versione:

`gpclient --version`

- Mostra aiuto per qualsiasi comando:

`gpclient help {{command}}`
