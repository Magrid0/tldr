# iwinfo

> Recupera informazioni sulle interfacce wireless su OpenWrt.
> Maggiori informazioni: <https://openwrt.org/docs/guide-developer/ubus/iwinfo>.

- Elenca tutte le interfacce wireless disponibili:

`iwinfo`

- Mostra informazioni dettagliate su un'interfaccia wireless specifica:

`iwinfo {{interface}} info`

- Scansiona le reti wireless vicine visibili all'interfaccia:

`iwinfo {{interface}} scan`

- Elenca i dispositivi connessi:

`iwinfo {{interface}} assoclist`

- Elenca i canali supportati dall'interfaccia:

`iwinfo {{interface}} freqlist`

- Elenca i livelli di potenza di trasmissione disponibili per l'interfaccia:

`iwinfo {{interface}} txpowerlist`

- Mostra aiuto:

`iwinfo h`
