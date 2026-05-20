# nft

> Permette la configurazione di tabelle, catene e regole fornite dal firewall del kernel Linux.
> Nftables sostituisce iptables.
> Maggiori informazioni: <https://wiki.nftables.org/wiki-nftables/index.php/Main_Page>.

- Visualizza la configurazione corrente:

`sudo nft list ruleset`

- Aggiunge una nuova tabella con famiglia "inet" e tabella "filter":

`sudo nft add table {{inet}} {{filter}}`

- Aggiunge una nuova catena per accettare tutto il traffico in entrata:

`sudo nft add chain {{inet}} {{filter}} {{input}} \{ type {{filter}} hook {{input}} priority {{0}} \; policy {{accept}} \; \}`

- Aggiunge una nuova regola per accettare diverse porte TCP:

`sudo nft add rule {{inet}} {{filter}} {{input}} {{tcp}} {{dport \{ telnet, ssh, http, https \} accept}}`

- Aggiunge una regola NAT per tradurre tutto il traffico dalla subnet `192.168.0.0/24` all'IP pubblico dell'host:

`sudo nft add rule {{nat}} {{postrouting}} ip saddr {{192.168.0.0/24}} {{masquerade}}`

- Mostra gli handle delle regole:

`sudo nft --handle --numeric list chain {{famiglia}} {{tabella}} {{catena}}`

- Elimina una regola:

`sudo nft delete rule {{inet}} {{filter}} {{input}} handle {{3}}`

- Salva la configurazione corrente:

`sudo nft list ruleset > {{/etc/nftables.conf}}`
