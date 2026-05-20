# imp

> Helper per usare il supporto nativo systemd in WSL (Windows Subsystem for Linux).
> Nota: per eseguire questi comandi da Windows anziché da una distribuzione già in esecuzione, precederli con `wsl`.
> Maggiori informazioni: <https://github.com/arkane-systems/bottle-imp#usage>.

- Inizializza le funzioni helper e mantiene WSL in esecuzione fino all'arresto esplicito (da eseguire una volta, all'avvio):

`imp {{[-i|--initialize]}}`

- Esegue una shell all'interno di una sessione utente systemd:

`imp {{[-s|--shell]}}`

- Esegue un comando specificato all'interno di una sessione utente systemd (mantiene la directory di lavoro):

`imp {{[-c|--command]}} {{command}}`

- Arresta systemd e l'istanza WSL:

`imp {{[-u|--shutdown]}}`
