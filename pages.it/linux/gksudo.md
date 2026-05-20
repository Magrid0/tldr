# gksudo

> Interfaccia per `sudo`.
> Esegue comandi grafici che necessitano di accesso root senza dover eseguire un emulatore di terminale X.
> Nota: Questo comando è deprecato in favore di comandi come `pkexec` e non è più mantenuto.
> Vedi anche: `gksu`.
> Maggiori informazioni: <https://manned.org/gksudo>.

- Esegue un comando come utente specifico:

`gksudo {{[-u|--user]}} {{userid}} {{command}}`

- Esegue il comando preservando gli ambienti correnti:

`gksudo {{[-u|--user]}} {{userid}} {{[-k|--preserve-env]}} {{command}}`

- Forza `gksudo` a usare `su` per eseguire il comando:

`gksu {{[-u|--user]}} {{userid}} {{[-w|--su-mode]}} {{command}}`

- Forza `gksudo` a usare `sudo` per eseguire il comando:

`gksudo {{[-u|--user]}} {{userid}} {{[-S|--sudo-mode]}} {{command}}`

- Mostra informazioni di debug per il comando indicato:

`gksudo {{[-u|--user]}} {{userid}} {{[-d|--debug]}} {{command}}`
