# xdp-filter

> Carica e gestisce un filtro di pacchetti eBPF XDP.
> Parte della collezione xdp-tools.
> Maggiori informazioni: <https://github.com/xdp-project/xdp-tools/tree/main/xdp-filter#running-xdp-filter>.

- Carica il filtro su un'interfaccia in modalità skb (generica) con politica di default allow:

`sudo xdp-filter load {{[-p|--policy]}} allow {{[-m|--mode]}} skb {{interfaccia_rete}}`

- Scarica il filtro da un'interfaccia:

`sudo xdp-filter unload {{interfaccia_rete}}`

- Nega il traffico verso una porta di destinazione specifica:

`sudo xdp-filter port {{porta_destinazione}}`

- Nega il traffico da un indirizzo IP sorgente specifico:

`sudo xdp-filter ip {{[-m|--mode]}} src {{indirizzo_ip_sorgente}}`

- Nega il traffico da un indirizzo MAC sorgente specifico:

`sudo xdp-filter ether {{[-m|--mode]}} src {{indirizzo_mac}}`

- Interroga i pacchetti e mostra le statistiche ogni 10000 millisecondi:

`sudo xdp-filter poll {{[-i|--interval]}} 10000`
