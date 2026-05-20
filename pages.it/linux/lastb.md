# lastb

> Elenca gli ultimi utenti che hanno effettuato l'accesso.
> Maggiori informazioni: <https://manned.org/lastb>.

- Elenca gli ultimi utenti che hanno effettuato l'accesso:

`sudo lastb`

- Elenca tutti gli ultimi accessi a partire da una data specifica:

`sudo lastb {{[-s|--since]}} {{YYYY-MM-DD}}`

- Elenca tutti gli ultimi accessi fino a una data specifica:

`sudo lastb {{[-t|--until]}} {{YYYY-MM-DD}}`

- Elenca tutti gli accessi a un'ora specifica:

`sudo lastb {{[-p|--present]}} {{hh:mm}}`

- Elenca tutti gli ultimi accessi e traduce l'IP in hostname:

`sudo lastb {{[-d|--dns]}}`
