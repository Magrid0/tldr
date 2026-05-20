# edquota

> Modifica le quote per un utente o un gruppo. Di default opera su tutti i filesystem con quote.
> Le informazioni sulle quote sono memorizzate permanentemente nei file `quota.user` e `quota.group` nella radice del filesystem.
> Maggiori informazioni: <https://manned.org/edquota>.

- Modifica la quota dell'utente corrente:

`edquota {{[-u|--user]}} $(whoami)`

- Modifica la quota di un utente specifico:

`sudo edquota {{[-u|--user]}} {{nome_utente}}`

- Modifica la quota per un gruppo:

`sudo edquota {{[-g|--group]}} {{gruppo}}`

- Limita le operazioni a un dato filesystem (di default edquota opera su tutti i filesystem con quote):

`sudo edquota {{[-f|--file-system]}} {{filesystem}}`

- Modifica il periodo di grazia predefinito:

`sudo edquota {{[-t|--edit-period]}}`

- Duplica una quota ad altri utenti:

`sudo edquota {{[-p|--prototype]}} {{utente_riferimento}} {{utente_destinazione1 utente_destinazione2 ...}}`
