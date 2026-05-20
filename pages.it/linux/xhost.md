# xhost

> Gestisce le liste di controllo accessi per le connessioni al server X.
> Maggiori informazioni: <https://manned.org/xhost>.

- Mostra la lista di controllo accessi corrente:

`xhost`

- Permetti a un host specifico di connettersi al server X:

`xhost +{{nome_host}}`

- Nega a un host specifico la connessione al server X:

`xhost -{{nome_host}}`

- Permetti a tutti gli host di connettersi (disabilita il controllo accessi - insicuro):

`xhost +`

- Nega tutti gli host tranne quelli esplicitamente permessi (abilita il controllo accessi):

`xhost -`

- Rimuovi un utente o indirizzo specifico usando un prefisso di famiglia (come `inet:hostname` o `si:localuser:username`):

`xhost -{{famiglia:nome}}`
