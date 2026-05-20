# cpulimit

> Uno strumento per limitare l'utilizzo della CPU di altri processi.
> Maggiori informazioni: <https://manned.org/cpulimit>.

- Limita un processo esistente con PID 1234 a utilizzare solo il 25% della CPU:

`cpulimit {{[-p|--pid]}} {{1234}} {{[-l|--limit]}} {{25%}}`

- Limita un programma esistente tramite il suo nome eseguibile:

`cpulimit {{[-e|--exe]}} {{program}} {{[-l|--limit]}} {{25}}`

- Avvia un dato programma e lo limita a utilizzare solo il 50% della CPU:

`cpulimit {{[-l|--limit]}} {{50}} -- {{program argument1 argument2 ...}}`

- Avvia un programma, limita il suo utilizzo della CPU al 50% ed esegue cpulimit in background:

`cpulimit {{[-l|--limit]}} {{50}} {{[-b|--background]}} -- {{program}}`

- Termina il suo processo se l'utilizzo della CPU del programma supera il 50%:

`cpulimit {{[-l|--limit]}} 50 {{[-k|--kill]}} -- {{program}}`

- Limita sia il programma che i suoi processi figli in modo che nessuno superi il 25% della CPU:

`cpulimit {{[-l|--limit]}} {{25}} {{[-m|--monitor-forks]}} -- {{program}}`
