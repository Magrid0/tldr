# usermod

> Modifica un account utente.
> Vedi anche: `users`, `useradd`, `userdel`.
> Maggiori informazioni: <https://manned.org/usermod>.

- Cambia un nome utente:

`sudo usermod {{[-l|--login]}} {{nuovo_nome_utente}} {{nome_utente}}`

- Cambia un ID utente:

`sudo usermod {{[-u|--uid]}} {{id}} {{nome_utente}}`

- Cambia la shell di un utente:

`sudo usermod {{[-s|--shell]}} {{percorso/della/shell}} {{nome_utente}}`

- Aggiungi un utente a gruppi supplementari (nota l'assenza di spazi):

`sudo usermod {{[-aG|--append --groups]}} {{gruppo1,gruppo2,...}} {{nome_utente}}`

- Rimuovi un utente da gruppi specifici:

`sudo usermod {{[-rG|--remove --groups]}} {{gruppo1,gruppo2,...}} {{nome_utente}}`

- Cambia la home directory di un utente:

`sudo usermod {{[-m|--move-home]}} {{[-d|--home]}} {{percorso/della/nuova_home}} {{nome_utente}}`

- Blocca un account:

`sudo usermod {{[-L|--lock]}} {{nome_utente}}`

- Sblocca un account:

`sudo usermod {{[-U|--unlock]}} {{nome_utente}}`
