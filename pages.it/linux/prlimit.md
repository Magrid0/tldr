# prlimit

> Ottiene o imposta i limiti soft e hard delle risorse di processo.
> Dato un ID processo e una o più risorse, prlimit cerca di recuperare e/o modificare i limiti.
> Maggiori informazioni: <https://manned.org/prlimit>.

- Mostra i valori dei limiti per tutte le risorse correnti del processo padre in esecuzione:

`prlimit`

- Mostra i valori dei limiti per tutte le risorse correnti di un processo specificato:

`prlimit {{[-p|--pid]}} {{numero_pid}}`

- Esegue un comando con un numero personalizzato di file aperti come limite:

`prlimit {{[-n|--nofile=]}}{{10}} {{comando}}`
