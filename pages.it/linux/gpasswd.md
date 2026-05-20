# gpasswd

> Amministra `/etc/group` e `/etc/gshadow`.
> Maggiori informazioni: <https://manned.org/gpasswd>.

- Definisce gli amministratori del gruppo:

`sudo gpasswd {{[-A|--administrators]}} {{user1,user2}} {{group}}`

- Imposta l'elenco dei membri del gruppo:

`sudo gpasswd {{[-M|--members]}} {{user1,user2}} {{group}}`

- Crea una password per il gruppo indicato:

`gpasswd {{group}}`

- Aggiunge un utente al gruppo indicato:

`gpasswd {{[-a|--add]}} {{user}} {{group}}`

- Rimuove un utente dal gruppo indicato:

`gpasswd {{[-d|--delete]}} {{user}} {{group}}`
