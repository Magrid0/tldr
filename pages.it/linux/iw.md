# iw

> Mostra e manipola i dispositivi wireless.
> Vedi anche: `iw dev`, `nmcli`, `iwctl`.
> Maggiori informazioni: <https://wireless.docs.kernel.org/en/latest/en/users/documentation/iw.html>.

- Cerca reti wireless disponibili:

`iw dev {{wlanX}} scan`

- Si connette a una rete wireless aperta:

`iw dev {{wlanX}} connect {{SSID}}`

- Chiude la connessione corrente:

`iw dev {{wlanX}} disconnect`

- Mostra informazioni sulla connessione corrente:

`iw dev {{wlanX}} link`

- Elenca tutte le interfacce di rete wireless fisiche e logiche:

`iw dev`

- Elenca tutte le capacità wireless per tutte le interfacce hardware fisiche:

`iw phy`

- Elenca le informazioni correnti sul dominio regolatorio wireless del kernel:

`iw reg get`

- Mostra aiuto:

`iw help`
