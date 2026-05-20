# nordvpn

> Interfaccia a riga di comando per NordVPN.
> Maggiori informazioni: <https://support.nordvpn.com/hc/articles/20196094470929-Installing-NordVPN-on-Linux-distributions>.

- Effettua il login interattivo a un account NordVPN:

`nordvpn login`

- Mostra lo stato della connessione:

`nordvpn status`

- Si connette al server NordVPN più vicino:

`nordvpn {{[c|connect]}}`

- Elenca tutti i paesi disponibili:

`nordvpn countries`

- Si connette a un server NordVPN in un paese specifico:

`nordvpn {{[c|connect]}} {{Germania}}`

- Si connette a un server NordVPN in un paese e città specifici:

`nordvpn {{[c|connect]}} {{Germania}} {{Berlino}}`

- Imposta l'opzione di connessione automatica:

`nordvpn {{[s|set]}} autoconnect on`
