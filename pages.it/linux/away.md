# away

> Blocca il terminale con un messaggio di assenza.
> Maggiori informazioni: <https://manned.org/away>.

- Blocca il terminale e imposta un messaggio di assenza:

`away {{messaggio}}`

- Blocca il terminale e abilita il controllo della posta:

`away {{[-c|--mail]}} {{messaggio}}`

- Blocca il terminale e disabilita il controllo della posta:

`away {{[-C|--nomail]}} {{messaggio}}`

- Blocca il terminale e sospende i processi in background per un numero di secondi:

`away {{[-t|--time]}} {{secondi}} {{messaggio}}`

- Blocca il terminale e controlla la posta se almeno una casella non ha ricevuto nuova posta:

`away {{[-p|--persist]}} {{messaggio}}`

- Blocca il terminale e controlla la posta fino a quando almeno una casella ha ricevuto nuova posta:

`away {{[-P|--nopersist]}} {{messaggio}}`

- Mostra aiuto:

`away {{[-h|--help]}}`

- Mostra versione:

`away {{[-v|--version]}}`
