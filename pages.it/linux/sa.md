# sa

> Riassume le informazioni di contabilità sui comandi chiamati dagli utenti, incluse informazioni base sul tempo di CPU speso e sui tassi di I/O.
> Fa parte del pacchetto `acct`.
> Maggiori informazioni: <https://manned.org/sa.8>.

- Mostra le invocazioni di eseguibili per utente (nome utente non mostrato):

`sudo sa`

- Mostra le invocazioni di eseguibili per utente, mostrando i nomi utente responsabili:

`sudo sa --print-users`

- Elenca le risorse usate recentemente per utente:

`sudo sa --user-summary`
