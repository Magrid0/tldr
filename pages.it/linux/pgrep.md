# pgrep

> Trova o invia segnali a processi per nome.
> Maggiori informazioni: <https://manned.org/pgrep>.

- Restituisce i PID di tutti i processi in esecuzione con un nome corrispondente:

`pgrep {{nome_processo}}`

- Mostra anche il comando completo:

`pgrep {{[-a|--list-full]}} {{nome_processo}}`

- Cerca processi includendo le loro opzioni da riga di comando:

`pgrep {{[-f|--full]}} "{{nome_processo}} {{parametro}}"`

- Cerca processi eseguiti da un utente specifico:

`pgrep {{[-u|--euid]}} {{nome_utente}} {{nome_processo}}`
