# register_new_matrix_user

> Registra nuovi utenti in un home server quando la registrazione è stata disabilitata.
> Maggiori informazioni: <https://manned.org/register_new_matrix_user>.

- Crea un utente in modo interattivo:

`register_new_matrix_user --config {{path/to/homeserver.yaml}}`

- Crea un utente amministratore in modo interattivo:

`register_new_matrix_user --config {{path/to/homeserver.yaml}} --admin`

- Crea un utente amministratore in modo non interattivo (non consigliato):

`register_new_matrix_user --config {{path/to/homeserver.yaml}} --user {{username}} --password {{password}} --admin`
