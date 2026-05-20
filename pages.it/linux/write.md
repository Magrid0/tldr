# write

> Scrive un messaggio sul terminale di un utente connesso specificato (`<Ctrl c>` per smettere di scrivere messaggi).
> Usa il comando `who` per scoprire tutti i terminal_id degli utenti attivi sul sistema.
> Vedi anche: `mesg`.
> Maggiori informazioni: <https://manned.org/write>.

- Invia un messaggio a un dato utente su un dato ID terminale:

`write {{nome_utente}} {{id_terminale}}`

- Invia un messaggio a "testuser" sul terminale `/dev/tty/5`:

`write {{testuser}} {{tty/5}}`

- Invia un messaggio a "johndoe" sul pseudo terminale `/dev/pts/5`:

`write {{johndoe}} {{pts/5}}`
