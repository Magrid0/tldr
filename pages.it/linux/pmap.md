# pmap

> Mostra la mappa di memoria di un processo o processi.
> Maggiori informazioni: <https://manned.org/pmap>.

- Mostra la mappa di memoria per un ID processo (PID) specifico:

`pmap {{pid}}`

- Mostra il formato esteso:

`pmap --extended {{pid}}`

- Mostra il formato dispositivo:

`pmap --device {{pid}}`

- Limita i risultati a un intervallo di indirizzi di memoria specificato da `low` e `high`:

`pmap --range {{low}},{{high}}`

- Mostra le mappe di memoria per più processi:

`pmap {{pid1 pid2 ...}}`
