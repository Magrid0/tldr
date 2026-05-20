# arptables

> Gestisce le regole di filtro ARP utilizzando il backend `nftables`.
> Parte della suite `xtables-nft` per il filtraggio dei pacchetti ARP.
> Maggiori informazioni: <https://manned.org/arptables>.

- Elenca tutte le regole ARP nella tabella di filtro:

`sudo arptables {{[-L|--list]}}`

- Aggiunge una regola per eliminare i pacchetti ARP da un indirizzo IP specifico:

`sudo arptables {{[-A|--append]}} INPUT {{[-s|--source-ip]}} {{192.168.0.1}} {{[-j|--jump]}} DROP`

- Elimina una regola specifica dalla catena INPUT tramite il suo numero di regola:

`sudo arptables {{[-D|--delete]}} INPUT {{numero_regola}}`

- Cancella tutte le regole nella tabella di filtro:

`sudo arptables {{[-F|--flush]}}`

- Imposta la politica predefinita della catena OUTPUT su ACCEPT:

`sudo arptables {{[-P|--policy]}} OUTPUT ACCEPT`

- Salva le regole ARP correnti in un file:

`sudo arptables-save > {{path/to/file}}`
