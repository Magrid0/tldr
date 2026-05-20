# kill

> Invia un segnale a un processo, di solito per fermarlo.
> Tutti i segnali tranne SIGKILL e SIGSTOP possono essere intercettati dal processo per eseguire una chiusura pulita.
> Maggiori informazioni: <https://manned.org/kill>.

- Termina un programma usando il segnale predefinito SIGTERM (termina):

`kill {{process_id}}`

- Elenca i valori dei segnali e i loro nomi corrispondenti (da usare senza il prefisso `SIG`). Le opzioni disponibili possono dipendere dall'implementazione di `kill`:

`kill {{-l|-L|--table}}`

- Termina un job in background:

`kill %{{job_id}}`

- Termina un programma usando il segnale SIGHUP (hang up). Molti demone ricaricheranno invece di terminare:

`kill {{[-1|-HUP]}} {{process_id}}`

- Termina un programma usando il segnale SIGINT (interrompi). Di solito viene iniziato dall'utente premendo `<Ctrl c>`:

`kill {{[-2|-INT]}} {{process_id}}`

- Segnala al sistema operativo di terminare immediatamente un programma (che non ha possibilità di catturare il segnale):

`kill {{[-9|-KILL]}} {{process_id}}`

- Segnala al sistema operativo di mettere in pausa un programma fino alla ricezione di un segnale SIGCONT ("continua"):

`kill {{[-19|-STOP]}} {{process_id}}`

- Invia un segnale `SIGUSR1` a tutti i processi con un dato GID (ID gruppo):

`kill -SIGUSR1 -{{group_id}}`
