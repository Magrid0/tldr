# nft monitor

> Mostra le modifiche in tempo reale all'interno del firewall Linux `nftables`.
> Maggiori informazioni: <https://manned.org/nft#head21>.

- Monitora tutti gli eventi di nftables:

`sudo nft monitor`

- Monitora solo gli aggiornamenti delle regole (aggiunta, eliminazione, sostituzione):

`sudo nft monitor rules`

- Monitora gli aggiornamenti di set ed elementi:

`sudo nft monitor sets`

- Monitora gli eventi e stampa l'output JSON:

`sudo nft {{[-j|--json]}} monitor`
