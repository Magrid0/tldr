# ncat

> Legge, scrive, reindirizza e crittografa dati attraverso una rete.
> Un'implementazione alternativa di un'utilità simile chiamata `netcat`/`nc`.
> Maggiori informazioni: <https://nmap.org/ncat/guide/index.html>.

- Ascolta input sulla porta specificata e lo scrive nel file specificato:

`ncat {{[-l|--listen]}} {{porta}} > {{percorso/del/file}}`

- Accetta più connessioni e mantiene ncat aperto dopo che sono state chiuse:

`ncat {{[-lk|--listen --keep-open]}} {{porta}}`

- Scrive l'output del file specificato all'host specificato sulla porta specificata:

`ncat < {{percorso/del/file}} {{indirizzo}} {{porta}}`

- Accetta più connessioni in entrata su un canale crittografato eludendo il rilevamento del contenuto del traffico:

`ncat --ssl {{[-k|--keep-open]}} {{[-l|--listen]}} {{porta}}`

- Si connette a una connessione `ncat` aperta tramite SSL:

`ncat --ssl {{host}} {{porta}}`

- Verifica la connettività a un host remoto su una porta particolare con timeout:

`ncat {{[-w|--wait]}} {{secondi}} {{[-vz|--verbose -z]}} {{host}} {{porta}}`
