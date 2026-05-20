# semanage

> Strumento di gestione persistente delle politiche SELinux.
> Alcuni sottocomandi come `boolean`, `fcontext`, `port`, ecc. hanno la propria documentazione d'uso.
> Maggiori informazioni: <https://manned.org/semanage>.

- Imposta o deseleziona un booleano SELinux. I booleani permettono all'amministratore di personalizzare come le regole delle politiche influenzano i tipi di processo confinati (noti anche come domini):

`sudo semanage boolean {{[-m|--modify]}} {{--on|--off}} {{haproxy_connect_any}}`

- Aggiunge una regola di etichettatura del contesto file definita dall'utente. I contesti file definiscono a quali file i domini confinati possono accedere:

`sudo semanage fcontext {{[-a|--add]}} {{[-t|--type]}} {{samba_share_t}} '/mnt/share(/.*)?'`

- Aggiunge una regola di etichettatura delle porte definita dall'utente. Le etichette delle porte definiscono su quali porte i domini confinati possono ascoltare:

`sudo semanage port {{[-a|--add]}} {{[-t|--type]}} {{ssh_port_t}} {{[-p|--proto]}} {{tcp}} {{22000}}`

- Imposta o deseleziona la modalità permissiva per un dominio confinato. La modalità permissiva per dominio permette un controllo più granulare rispetto a `setenforce`:

`sudo semanage permissive {{--add|--delete}} {{httpd_t}}`

- Produce le personalizzazioni locali nell'archivio predefinito:

`sudo semanage export {{[-f|--output_file]}} {{percorso/del/file}}`

- Importa un file generato da `semanage export` nelle personalizzazioni locali (ATTENZIONE: potrebbe rimuovere le personalizzazioni correnti!):

`sudo semanage import {{[-f|--input_file]}} {{percorso/del/file}}`
