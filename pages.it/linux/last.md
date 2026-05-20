# last

> Visualizza gli ultimi utenti che hanno effettuato l'accesso.
> Maggiori informazioni: <https://manned.org/last>.

- Visualizza le informazioni dell'ultimo accesso (es. nome utente, terminale, ora di avvio, kernel) di tutti gli utenti lette da `/var/log/wtmp`:

`last`

- Elenca le informazioni di accesso di un utente specifico:

`last {{username}}`

- Specifica quanti degli ultimi accessi mostrare:

`last {{[-n|--limit]}} {{login_count}}`

- Stampa la data e l'ora complete per le voci e mostra l'ultima colonna dell'hostname per evitare troncamenti:

`last {{[-F|--fulltimes]}} {{[-a|--hostlast]}}`

- Visualizza tutti gli accessi di un utente specifico e mostra l'indirizzo IP invece dell'hostname:

`last {{username}} {{[-i|--ip]}}`

- Elenca le informazioni da un momento e data specifici:

`last {{[-s|--since]}} {{-7days}}`

- Visualizza tutti i riavvii registrati (cioè gli ultimi accessi dell'utente fittizio "reboot"):

`last reboot`

- Mostra aiuto:

`last {{[-h|--help]}}`
