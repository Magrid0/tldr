# iwconfig

> Configura e mostra i parametri di un'interfaccia di rete wireless.
> Maggiori informazioni: <https://manned.org/iwconfig>.

- Mostra i parametri e le statistiche di tutte le interfacce:

`iwconfig`

- Mostra i parametri e le statistiche dell'interfaccia specificata:

`iwconfig {{interface}}`

- Imposta l'ESSID (nome della rete) dell'interfaccia specificata (es. `eth0` o `wlan0`):

`iwconfig {{interface}} {{new_network_name}}`

- Imposta la modalità operativa dell'interfaccia specificata:

`iwconfig {{interface}} mode {{Ad-Hoc|Managed|Master|Repeater|Secondary|Monitor|Auto}}`
