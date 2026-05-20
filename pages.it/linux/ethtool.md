# ethtool

> Mostra e modifica i parametri del Controller d'Interfaccia di Rete (NIC).
> Maggiori informazioni: <https://manned.org/ethtool>.

- Mostra le impostazioni correnti per un'interfaccia:

`ethtool {{eth0}}`

- Mostra le informazioni sul driver per un'interfaccia:

`ethtool {{[-i|--driver]}} {{eth0}}`

- Mostra tutte le funzionalità supportate per un'interfaccia:

`ethtool {{[-k|--show-features]}} {{eth0}}`

- Mostra le statistiche di utilizzo della rete per un'interfaccia:

`ethtool {{[-S|--statistics]}} {{eth0}}`

- Fa lampeggiare uno o più LED su un'interfaccia per 10 secondi:

`ethtool {{[-p|--identify]}} {{eth0}} {{10}}`

- Imposta la velocità del collegamento, la modalità duplex e l'auto-negazione dei parametri per un'interfaccia data:

`ethtool {{[-s|--change]}} {{eth0}} speed {{10|100|1000}} duplex {{half|full}} autoneg {{on|off}}`
