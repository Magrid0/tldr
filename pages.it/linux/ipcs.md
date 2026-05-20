# ipcs

> Mostra informazioni sull'uso delle strutture IPC System V: segmenti di memoria condivisa, code di messaggi e array di semafori.
> Vedi anche: `lsipc`, `ipcmk`, `ipcrm`.
> Maggiori informazioni: <https://manned.org/ipcs>.

- Mostra informazioni su tutte le strutture IPC attive:

`ipcs`

- Mostra informazioni sui segmenti di memoria condivisa [m], code di messaggi [q] o set di semafori [s] attivi:

`ipcs {{--shmems|--queues|--semaphores}}`

- Mostra i dettagli completi della risorsa con un ID specifico:

`ipcs {{--shmems|--queues|--semaphores}} {{[-i|--id]}} {{resource_id}}`

- Mostra i limiti in [b]yte o in formato leggibile:

`ipcs {{[-l|--limits]}} {{--bytes|--human}}`

- Mostra un riepilogo sull'uso corrente:

`ipcs {{[-u|--summary]}}`

- Mostra gli UID e i PID del creatore e del proprietario per tutte le strutture IPC:

`ipcs {{[-c|--creator]}}`

- Mostra il PID degli ultimi operatori per tutte le strutture IPC:

`ipcs {{[-p|--pid]}}`

- Mostra gli orari dell'ultimo accesso per tutte le strutture IPC:

`ipcs {{[-t|--time]}}`
