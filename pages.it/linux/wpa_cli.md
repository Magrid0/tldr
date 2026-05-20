# wpa_cli

> Aggiungi e configura interfacce Wi-Fi.
> Maggiori informazioni: <https://manned.org/wpa_cli>.

- Cerca reti disponibili:

`sudo wpa_cli scan`

- Mostra i risultati della scansione:

`sudo wpa_cli scan_results`

- Aggiungi una rete:

`sudo wpa_cli {{[add_n|add_network]}} {{numero}}`

- Imposta l'SSID di una rete:

`sudo wpa_cli {{[set_n|set_network]}} {{numero}} ssid "{{SSID}}"`

- Abilita la rete:

`sudo wpa_cli {{[en|enable_network]}} {{numero}}`

- Salva la configurazione:

`sudo wpa_cli {{[sa|save_config]}}`
