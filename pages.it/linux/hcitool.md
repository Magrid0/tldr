# hcitool

> Monitora, configura connessioni e invia comandi speciali a dispositivi Bluetooth.
> Maggiori informazioni: <https://manned.org/hcitool>.

- Cerca dispositivi Bluetooth:

`hcitool scan`

- Mostra il nome di un dispositivo, restituendo il suo indirizzo MAC:

`hcitool name {{bdaddr}}`

- Recupera informazioni su un dispositivo Bluetooth remoto:

`hcitool info {{bdaddr}}`

- Controlla la qualità del collegamento a un dispositivo Bluetooth:

`hcitool lq {{bdaddr}}`

- Modifica il livello di potenza di trasmissione:

`hcitool tpl {{bdaddr}} {{0|1}}`

- Mostra la politica di collegamento:

`hcitool lp`

- Richiede l'autenticazione con un dispositivo specifico:

`hcitool auth {{bdaddr}}`

- Mostra i dispositivi locali:

`hcitool dev`
