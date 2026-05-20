# nmcli networking

> Gestisce lo stato di rete di NetworkManager.
> Maggiori informazioni: <https://networkmanager.pages.freedesktop.org/NetworkManager/NetworkManager/nmcli.html#networking>.

- Mostra lo stato di rete di NetworkManager:

`nmcli {{[n|networking]}}`

- Abilita o disabilita la rete e tutte le interfacce gestite da NetworkManager:

`nmcli {{[n|networking]}} {{on|off}}`

- Mostra l'ultimo stato di connettività noto:

`nmcli {{[n|networking]}} {{[c|connectivity]}}`

- Mostra lo stato di connettività corrente:

`nmcli {{[n|networking]}} {{[c|connectivity]}} {{[c|check]}}`
