# opkg

> Un gestore di pacchetti leggero usato per installare pacchetti OpenWrt.
> Maggiori informazioni: <https://openwrt.org/docs/guide-user/additional-software/opkg>.

- Installa un pacchetto:

`opkg install {{pacchetto}}`

- Rimuove un pacchetto:

`opkg remove {{pacchetto}}`

- Aggiorna la lista dei pacchetti disponibili:

`opkg update`

- Aggiorna uno o più pacchetti specifici:

`opkg upgrade {{pacchetto1 pacchetto2 ...}}`

- Mostra informazioni per un pacchetto specifico:

`opkg info {{pacchetto}}`

- Elenca tutti i pacchetti disponibili:

`opkg list`

- Trova a quale pacchetto appartiene un file:

`opkg search /{{percorso/del/file}}`

- Elenca tutti i file appartenenti a un pacchetto:

`opkg files {{pacchetto}}`
