# ubus

> Interagisci con un server OpenWrt ubusd.
> Maggiori informazioni: <https://openwrt.org/docs/techref/ubus>.

- Elenca gli oggetti disponibili:

`ubus list`

- Recupera le informazioni di sistema in formato JSON:

`ubus call system board`

- Ascolta gli eventi:

`ubus subscribe {{nome_evento}}`

- Mostra aiuto:

`ubus`
