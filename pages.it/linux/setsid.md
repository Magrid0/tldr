# setsid

> Esegue un programma in una nuova sessione se il processo chiamante non è un capogruppo di processo.
> La sessione creata non è controllata dal terminale corrente per impostazione predefinita.
> Maggiori informazioni: <https://manned.org/setsid>.

- Esegue un programma in una nuova sessione:

`setsid {{programma}}`

- Esegue un programma in una nuova sessione scartando l'output e l'errore risultanti:

`setsid {{programma}} > /dev/null 2>&1`

- Esegue un programma creando un nuovo processo:

`setsid {{[-f|--fork]}} {{programma}}`

- Restituisce il codice di uscita di un programma come codice di uscita di setsid quando il programma termina:

`setsid {{[-w|--wait]}} {{programma}}`

- Esegue un programma in una nuova sessione impostando il terminale corrente come terminale di controllo:

`setsid {{[-c|--ctty]}} {{programma}}`
