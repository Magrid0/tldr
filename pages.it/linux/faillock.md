# faillock

> Mostra e modifica i file dei record di autenticazione falliti.
> Maggiori informazioni: <https://manned.org/faillock>.

- Elenca i tentativi di login falliti per l'utente corrente:

`faillock`

- Resetta i record di fallimenti per l'utente corrente:

`faillock --reset`

- Elenca i tentativi di login falliti per tutti gli utenti:

`sudo faillock`

- Elenca i tentativi di login falliti per un utente specifico:

`sudo faillock --user {{user}}`

- Resetta i record di fallimenti per un utente specifico:

`sudo faillock --user {{user}} --reset`
