# chage

> Modifica le informazioni sulla scadenza dell'account utente e della password.
> Maggiori informazioni: <https://manned.org/chage>.

- Elenca le informazioni sulla password per l'utente:

`chage {{[-l|--list]}} {{username}}`

- Abilita la scadenza della password tra 10 giorni:

`sudo chage {{[-M|--maxdays]}} {{10}} {{username}}`

- Disabilita la scadenza della password:

`sudo chage {{[-M|--maxdays]}} {{-1}} {{username}}`

- Imposta la data di scadenza dell'account:

`sudo chage {{[-E|--expiredate]}} {{YYYY-MM-DD}} {{username}}`

- Forza l'utente a cambiare la password al prossimo accesso:

`sudo chage {{[-d|--lastday]}} {{0}} {{username}}`

- Riattiva un account:

`sudo chage {{[-E|--expiredate]}} -1 {{username}}`
