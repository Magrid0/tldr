# groupadd

> Aggiunge gruppi di utenti al sistema.
> Vedi anche: `groups`, `groupdel`, `groupmod`.
> Maggiori informazioni: <https://manned.org/groupadd>.

- Crea un nuovo gruppo:

`sudo groupadd {{group_name}}`

- Crea un nuovo gruppo di sistema:

`sudo groupadd {{[-r|--system]}} {{group_name}}`

- Crea un nuovo gruppo con l'ID gruppo specifico:

`sudo groupadd {{[-g|--gid]}} {{id}} {{group_name}}`
