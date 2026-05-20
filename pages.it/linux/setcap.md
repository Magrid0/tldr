# setcap

> Imposta le capacità di un file specificato.
> Vedi anche: `getcap`.
> Maggiori informazioni: <https://manned.org/setcap>.

- Imposta la capacità `cap_net_raw` (per usare socket RAW e PACKET) per un dato file:

`setcap '{{cap_net_raw}}' {{percorso/del/file}}`

- Imposta capacità multiple su un file (`ep` dopo la capacità significa "effettivo permesso"):

`setcap '{{cap_dac_read_search,cap_sys_tty_config+ep}}' {{percorso/del/file}}`

- Rimuove tutte le capacità da un file:

`setcap -r {{percorso/del/file}}`

- Verifica che le capacità specificate siano attualmente associate al file specificato:

`setcap -v '{{cap_net_raw}}' {{percorso/del/file}}`

- L'argomento opzionale `-n root_uid` può essere usato per impostare la capacità del file per l'uso solo in un namespace utente con questo proprietario root UID:

`setcap -n {{root_uid}} '{{cap_net_admin}}' {{percorso/del/file}}`
