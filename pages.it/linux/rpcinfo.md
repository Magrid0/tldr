# rpcinfo

> Effettua una chiamata RPC a un server RPC e riporta ciò che trova.
> Maggiori informazioni: <https://manned.org/rpcinfo>.

- Mostra la tabella completa di tutti i servizi RPC registrati su localhost:

`rpcinfo`

- Mostra la tabella concisa di tutti i servizi RPC registrati su localhost:

`rpcinfo -s {{localhost}}`

- Mostra la tabella delle statistiche delle operazioni rpcbind su localhost:

`rpcinfo -m`

- Mostra l'elenco delle voci del nome del servizio specificato (mountd) e del numero di versione (2) su una condivisione NFS remota:

`rpcinfo -l {{remote_nfs_server_ip}} {{mountd}} {{2}}`

- Elimina la registrazione per la versione 1 del servizio mountd per tutti i trasporti:

`rpcinfo -d {{mountd}} {{1}}`
