# bmon

> Monitora la larghezza di banda e cattura statistiche relative alla rete.
> Maggiori informazioni: <https://manned.org/bmon>.

- Mostra l'elenco di tutte le interfacce:

`bmon {{[-a|--show-all]}}`

- Mostra i tassi di trasferimento dati in bit al secondo:

`bmon {{[-b|--use-bit]}}`

- Specifica la politica per definire quali interfacce di rete vengono mostrate:

`bmon {{[-p|--policy]}} {{interface_1,interface_2,interface_3,...}}`

- Specifica l'intervallo (in secondi) in cui viene calcolato il tasso per contatore:

`bmon {{[-R|--rate-interval]}} {{2.0}}`
