# nmcli agent

> Esegue `nmcli` come agente segreto di NetworkManager o agente polkit.
> Maggiori informazioni: <https://networkmanager.pages.freedesktop.org/NetworkManager/NetworkManager/nmcli.html#agent>.

- Registra `nmcli` come agente segreto e resta in ascolto per richieste segrete:

`nmcli {{[a|agent]}} {{[s|secret]}}`

- Registra `nmcli` come agente polkit e resta in ascolto per richieste di autorizzazione:

`nmcli {{[a|agent]}} {{[p|polkit]}}`

- Registra `nmcli` come agente segreto e agente polkit:

`nmcli {{[a|agent]}} {{[a|all]}}`
