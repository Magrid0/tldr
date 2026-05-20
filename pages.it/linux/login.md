# login

> Avvia una sessione per un utente.
> Maggiori informazioni: <https://manned.org/login>.

- Accede come utente:

`login {{user}}`

- Accede come utente senza autenticazione se l'utente è già autenticato:

`login -f {{user}}`

- Accede come utente e preserva l'ambiente:

`login -p {{user}}`

- Accede come utente su un host remoto:

`login -h {{host}} {{user}}`
