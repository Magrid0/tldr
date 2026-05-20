# ausearch

> Interroga il log di audit Linux per eventi.
> Parte del pacchetto `audit`.
> Vedi anche: `audit2why`, `audit2allow`, `aureport`.
> Maggiori informazioni: <https://manned.org/ausearch>.

- Cerca tutti gli eventi di rifiuto SELinux AVC:

`sudo ausearch {{[-m|--message]}} avc`

- Cerca eventi relativi a un eseguibile specifico:

`sudo ausearch {{[-c|--comm]}} {{httpd}}`

- Cerca eventi da un utente specifico:

`sudo ausearch {{[-ui|--uid]}} {{1000}}`

- Cerca eventi negli ultimi 10 minuti:

`sudo ausearch {{[-ts|--start]}} recent`

- Cerca tentativi di accesso falliti:

`sudo ausearch {{[-m|--message]}} user_login {{[-sv|--success]}} no`

- Cerca eventi relativi a un file specifico:

`sudo ausearch {{[-f|--file]}} {{path/to/file}}`

- Mostra i risultati in formato raw per ulteriore elaborazione:

`sudo ausearch {{[-m|--message]}} avc --raw`
