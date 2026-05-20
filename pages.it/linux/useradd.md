# useradd

> Crea un nuovo utente.
> Vedi anche: `users`, `userdel`, `usermod`.
> Maggiori informazioni: <https://manned.org/useradd>.

- Crea un nuovo utente:

`sudo useradd {{nome_utente}}`

- Crea un nuovo utente con l'ID utente specificato:

`sudo useradd {{[-u|--uid]}} {{id}} {{nome_utente}}`

- Crea un nuovo utente con la shell specificata:

`sudo useradd {{[-s|--shell]}} {{percorso/della/shell}} {{nome_utente}}`

- Crea un nuovo utente appartenente a gruppi aggiuntivi (nota l'assenza di spazi):

`sudo useradd {{[-G|--groups]}} {{gruppo1,gruppo2,...}} {{nome_utente}}`

- Crea un nuovo utente con la home directory predefinita:

`sudo useradd {{[-m|--create-home]}} {{nome_utente}}`

- Crea un nuovo utente con la home directory riempita dai file della directory template:

`sudo useradd {{[-k|--skel]}} {{percorso/della/directory_template}} {{[-m|--create-home]}} {{nome_utente}}`

- Crea un nuovo utente di sistema senza home directory:

`sudo useradd {{[-r|--system]}} {{nome_utente}}`
