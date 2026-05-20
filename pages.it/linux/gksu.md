# gksu

> Interfaccia per `su`.
> Esegue comandi grafici che necessitano di accesso root senza dover eseguire un emulatore di terminale X.
> Nota: Questo comando è deprecato in favore di comandi come `pkexec` e non è più mantenuto.
> Vedi anche: `gksudo`.
> Maggiori informazioni: <https://manned.org/gksu>.

- Esegue un comando come utente specifico:

`gksu {{[-u|--user]}} {{userid}} {{command}}`

- Esegue il comando preservando gli ambienti correnti:

`gksu {{[-u|--user]}} {{userid}} {{[-k|--preserve-env]}} {{command}}`

- Forza `gksu` a usare `su` per eseguire il comando:

`gksu {{[-u|--user]}} {{userid}} {{[-w|--su-mode]}} {{command}}`

- Forza `gksu` a usare `sudo` per eseguire il comando:

`gksu {{[-u|--user]}} {{userid}} {{[-S|--sudo-mode]}} {{command}}`

- Mostra informazioni di debug per il comando indicato:

`gksu {{[-u|--user]}} {{userid}} {{[-d|--debug]}} {{command}}`
