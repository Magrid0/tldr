# choom

> Mostra e modifica il punteggio di adattamento dell'out-of-memory killer.
> Maggiori informazioni: <https://manned.org/choom>.

- Mostra il punteggio OOM-killer del processo con un ID specifico:

`choom {{[-p|--pid]}} {{pid}}`

- Modifica il punteggio OOM-killer di adattamento di un processo specifico:

`choom {{[-p|--pid]}} {{pid}} {{[-n|--adjust]}} {{-1000..+1000}}`

- Esegue un comando con un punteggio OOM-killer di adattamento specifico:

`choom {{[-n|--adjust]}} {{-1000..+1000}} {{command}} {{argument1 argument2 ...}}`
