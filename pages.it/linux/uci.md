# uci

> Gestisci i file di configurazione di OpenWrt.
> Maggiori informazioni: <https://openwrt.org/docs/techref/uci>.

- Recupera un valore:

`uci get {{network.lan.ipaddr}}`

- Elenca tutte le opzioni e i loro valori:

`uci show {{network}}`

- Imposta un valore:

`uci set {{config}}.{{sezione}}.{{opzione}}={{valore}}`

- Aggiungi una nuova sezione:

`uci add {{config}} {{sezione}}`

- Elimina una sezione o un valore:

`uci delete {{config}}.{{sezione}}.{{opzione}}`

- Conferma le modifiche:

`uci commit {{config}}`

- Annulla le modifiche non confermate:

`uci revert {{config}}`

- Mostra aiuto:

`uci`
