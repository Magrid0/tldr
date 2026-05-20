# loginctl

> Gestisce il gestore di login systemd.
> Vedi anche: `lslogins`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/loginctl.html>.

- Stampa tutte le sessioni correnti:

`loginctl`

- Stampa tutte le proprietà di una sessione specifica:

`loginctl show-session {{session_id}} {{[-a|--all]}}`

- Stampa tutte le proprietà di un utente specifico:

`loginctl show-user {{username}}`

- Stampa una proprietà specifica di un utente:

`loginctl show-user {{username}} {{[-p|--property]}} {{property_name}}`

- Esegue un'operazione `loginctl` su un host remoto:

`loginctl list-users {{[-H|--host]}} {{hostname}}`

- Disconnette un utente da tutte le sue sessioni:

`loginctl terminate-user {{username}}`

- Mostra aiuto:

`loginctl {{[-h|--help]}}`
