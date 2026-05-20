# nmcli radio

> Mostra lo stato degli interruttori radio o li abilita/disabilita usando NetworkManager.
> Maggiori informazioni: <https://networkmanager.pages.freedesktop.org/NetworkManager/NetworkManager/nmcli.html#radio>.

- Mostra lo stato del Wi-Fi:

`nmcli {{[r|radio]}} {{[w|wifi]}}`

- Accende o spegne il Wi-Fi:

`nmcli {{[r|radio]}} {{[w|wifi]}} {{on|off}}`

- Mostra lo stato del WWAN:

`nmcli {{[r|radio]}} {{[ww|wwan]}}`

- Accende o spegne il WWAN:

`nmcli {{[r|radio]}} {{[ww|wwan]}} {{on|off}}`

- Mostra lo stato di entrambi gli interruttori:

`nmcli {{[r|radio]}}`

- Accende o spegne entrambi gli interruttori:

`nmcli {{[r|radio]}} {{[a|all]}} {{on|off}}`
