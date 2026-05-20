# dbclient

> Client SSH leggero Dropbear.
> Maggiori informazioni: <https://manned.org/dbclient>.

- Si connette a un host remoto:

`dbclient {{user}}@{{host}}`

- Si connette a un host remoto sulla [p]orta 2222:

`dbclient {{user}}@{{host}} -p 2222`

- Si connette a un host remoto usando una chiave [i]dentity specifica in formato Dropbear:

`dbclient -i {{path/to/key_file}} {{user}}@{{host}}`

- Esegue un comando sull'host remoto con allocazione di [t]ty che permette l'interazione con il comando remoto:

`dbclient {{user}}@{{host}} -t {{command}} {{argument1 argument2 ...}}`

- Si connette e inoltra connessioni [A]gent all'host remoto:

`dbclient -A {{user}}@{{host}}`
