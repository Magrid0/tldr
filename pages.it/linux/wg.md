# wg

> Gestisci la configurazione delle interfacce WireGuard.
> Maggiori informazioni: <https://www.wireguard.com/quickstart/>.

- Controlla lo stato delle interfacce attualmente attive:

`sudo wg`

- Genera una nuova chiave privata:

`wg genkey`

- Genera una chiave pubblica da una chiave privata:

`wg < {{percorso/della/chiave_privata}} pubkey > {{percorso/della/chiave_pubblica}}`

- Genera una chiave pubblica e privata:

`wg genkey | tee {{percorso/della/chiave_privata}} | wg pubkey > {{percorso/della/chiave_pubblica}}`

- Mostra la configurazione corrente di un'interfaccia wireguard:

`sudo wg showconf {{wg0}}`
