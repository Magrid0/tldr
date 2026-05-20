# iw dev

> Mostra e manipola i dispositivi wireless.
> Per un elenco di canali, frequenze e informazioni regolatorie: <https://wireless.docs.kernel.org/en/latest/en/developers/documentation/channellist.html>.
> Maggiori informazioni: <https://wireless.docs.kernel.org/en/latest/en/users/documentation/iw.html>.

- Imposta il dispositivo in modalità monitor (l'interfaccia deve prima essere disattivata. Vedi anche: `ip link`):

`sudo iw dev {{wlanX}} set type monitor`

- Imposta il dispositivo in modalità managed (l'interfaccia deve prima essere disattivata):

`sudo iw dev {{wlanX}} set type managed`

- Imposta il canale Wi-Fi del dispositivo (il dispositivo deve prima essere in modalità monitor con l'interfaccia attiva):

`sudo iw dev {{wlanX}} set channel {{channel_number}}`

- Imposta la frequenza Wi-Fi del dispositivo in MHz (il dispositivo deve prima essere in modalità monitor con l'interfaccia attiva):

`sudo iw dev {{wlanX}} set freq {{freq_in_mhz}}`

- Mostra tutte le informazioni conosciute della stazione:

`iw dev {{wlanX}} station dump`

- Crea un'interfaccia virtuale in modalità monitor con un indirizzo MAC specifico:

`sudo iw dev {{wlanX}} interface add "{{vif_name}}" type monitor addr {{12:34:56:aa:bb:cc}}`

- Elimina l'interfaccia virtuale:

`sudo iw dev "{{vif_name}}" del`
