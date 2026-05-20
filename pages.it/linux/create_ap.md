# create_ap

> Crea un AP (Access Point) su qualsiasi canale.
> Maggiori informazioni: <https://github.com/oblique/create_ap>.

- Crea una rete aperta senza passphrase:

`create_ap {{wlan0}} {{eth0}} {{access_point_ssid}}`

- Utilizza una passphrase WPA + WPA2:

`create_ap {{wlan0}} {{eth0}} {{access_point_ssid}} {{passphrase}}`

- Crea un access point senza condivisione Internet:

`create_ap -n {{wlan0}} {{access_point_ssid}} {{passphrase}}`

- Crea una rete in bridge con condivisione Internet:

`create_ap -m bridge {{wlan0}} {{eth0}} {{access_point_ssid}} {{passphrase}}`

- Crea una rete in bridge con condivisione Internet e un'interfaccia bridge preconfigurata:

`create_ap -m bridge {{wlan0}} {{br0}} {{access_point_ssid}} {{passphrase}}`

- Crea un access point per la condivisione Internet dalla stessa interfaccia Wi-Fi:

`create_ap {{wlan0}} {{wlan0}} {{access_point_ssid}} {{passphrase}}`

- Sceglie un driver adattatore Wi-Fi diverso:

`create_ap --driver {{wifi_adapter}} {{wlan0}} {{eth0}} {{access_point_ssid}} {{passphrase}}`
