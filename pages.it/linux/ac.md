# ac

> Stampa statistiche su quanto tempo gli utenti sono stati connessi.
> Maggiori informazioni: <https://www.gnu.org/software/acct/manual/accounting.html#ac>.

- Stampa da quanto tempo l'utente corrente è connesso in ore:

`ac`

- Stampa da quanto tempo gli utenti sono connessi in ore:

`ac {{[-p|--individual-totals]}}`

- Stampa da quanto tempo un utente specifico è connesso in ore:

`ac {{[-p|--individual-totals]}} {{nome_utente}}`

- Stampa da quanto tempo un utente specifico è connesso in ore al giorno (con totale):

`ac {{[-d|--daily-totals]}} {{[-p|--individual-totals]}} {{nome_utente}}`

- Mostra anche dettagli aggiuntivi:

`ac --compatibility`
