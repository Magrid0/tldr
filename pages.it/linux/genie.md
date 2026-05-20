# genie

> Imposta e utilizza un namespace "bottle" per eseguire systemd sotto WSL (Windows Subsystem for Linux).
> Per eseguire questi comandi da Windows anziché da una distribuzione già in esecuzione, precedili con `wsl`.
> Maggiori informazioni: <https://github.com/arkane-systems/genie>.

- Inizializza il bottle (esegui una volta, all'avvio):

`genie {{[-i|--initialize]}}`

- Esegue una shell di login all'interno del bottle:

`genie {{[-s|--shell]}}`

- Esegue un comando specificato all'interno del bottle:

`genie {{[-c|--command]}} {{command}}`
