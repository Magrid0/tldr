# lure

> Un sistema di build e repository utente per Linux indipendente dalla distribuzione.
> Maggiori informazioni: <https://github.com/lure-sh/lure/blob/master/docs/usage.md>.

- Installa un pacchetto:

`lure {{[in|install]}} {{package}}`

- Rimuove un pacchetto:

`lure {{[rm|remove]}} {{package}}`

- Aggiorna i pacchetti:

`lure {{[up|upgrade]}}`

- Elenca tutti i pacchetti disponibili:

`lure {{[ls|list]}}`

- Scarica tutti i repository che sono cambiati:

`lure {{[ref|refresh]}}`

- Aggiunge un nuovo repository:

`lure {{[ar|addrepo]}} {{[-n|--name]}} {{repository_name}} --url {{repository_url}}`

- Rimuove un repository esistente:

`lure {{[rr|removerepo]}} {{[-n|--name]}} {{repository_name}}`

- Compila un pacchetto:

`lure build -s {{path/to/script}}`
