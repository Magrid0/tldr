# nmcli connection

> Gestisce le connessioni con NetworkManager.
> Maggiori informazioni: <https://networkmanager.pages.freedesktop.org/NetworkManager/NetworkManager/nmcli.html#connection>.

- Elenca tutte le connessioni di NetworkManager (mostra nome, UUID, tipo e dispositivo):

`nmcli {{[c|connection]}}`

- Attiva una connessione:

`nmcli {{[c|connection]}} {{[u|up]}} {{uuid}}`

- Disattiva una connessione:

`nmcli {{[c|connection]}} {{[d|down]}} {{uuid}}`

- Crea una connessione dual stack configurata automaticamente:

`nmcli {{[c|connection]}} {{[a|add]}} ifname {{nome_interfaccia}} type {{ethernet}} ipv4.method {{auto}} ipv6.method {{auto}}`

- Crea una connessione statica solo IPv6:

`nmcli {{[c|connection]}} {{[a|add]}} ifname {{nome_interfaccia}} type {{ethernet}} ip6 {{2001:db8::2/64}} gw6 {{2001:db8::1}} ipv6.dns {{2001:db8::1}} ipv4.method {{ignore}}`

- Crea una connessione statica solo IPv4:

`nmcli {{[c|connection]}} {{[a|add]}} ifname {{nome_interfaccia}} type {{ethernet}} ip4 {{10.0.0.7/8}} gw4 {{10.0.0.1}} ipv4.dns {{10.0.0.1}} ipv6.method {{ignore}}`

- Crea una connessione VPN usando OpenVPN da un file OVPN:

`nmcli {{[c|connection]}} {{[i|import]}} type {{openvpn}} file {{percorso/della/config_vpn.ovpn}}`
