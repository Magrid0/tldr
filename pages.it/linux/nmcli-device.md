# nmcli device

> Gestisce le interfacce di rete e stabilisce nuove connessioni Wi-Fi usando NetworkManager.
> Maggiori informazioni: <https://networkmanager.pages.freedesktop.org/NetworkManager/NetworkManager/nmcli.html#device>.

- Stampa lo stato di tutte le interfacce di rete:

`nmcli {{[d|device]}}`

- Stampa i punti di accesso Wi-Fi disponibili:

`nmcli {{[d|device]}} {{[w|wifi]}}`

- Si connette a una rete Wi-Fi con l'SSID specificato (verrà chiesta una password):

`nmcli {{[d|device]}} {{[w|wifi]}} {{[c|connect]}} {{ssid}} {{[-a|--ask]}}`

- Crea un hotspot Wi-Fi:

`nmcli {{[d|device]}} {{[w|wifi]}} {{[ho|hotspot]}} ifname {{wlan0}} ssid "{{hotspot_ssid}}" password "{{password}}"`

- Stampa la password e il codice QR per la rete Wi-Fi corrente:

`nmcli {{[d|device]}} {{[w|wifi]}} {{[s|show-password]}}`

- Stampa informazioni dettagliate su un dispositivo:

`nmcli {{[d|device]}} {{[sh|show]}} {{wlan0}}`
