# tftp

> Client del Trivial File Transfer Protocol.
> Maggiori informazioni: <https://manned.org/tftp>.

- Connettiti a un server TFTP con una shell interattiva, specificando il suo indirizzo IP e la porta:

`tftp {{ip_server}} {{porta}}`

- Connettiti a un server TFTP ed esegui un [c]omando TFTP:

`tftp {{ip_server}} -c {{comando}}`

- Connettiti a un server TFTP usando IPv6 e forza la porta di origine a rientrare in un [R]ange:

`tftp {{ip_server}} -6 -R {{porta}}:{{porta}}`

- [Interactive] Imposta la modalità di trasferimento su binary o ASCII tramite il client tftp:

`mode {{binary|ascii}}`

- [Interactive] Scarica un file da un server tramite il client tftp:

`get {{file}}`

- [Interactive] Carica un file su un server tramite il client tftp:

`put {{file}}`

- [Interactive] Esci dal client tftp:

`quit`
