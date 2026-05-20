# lsipc

> Mostra informazioni sulle strutture IPC System V attualmente in uso nel sistema.
> Vedi anche: `ipcs`.
> Maggiori informazioni: <https://manned.org/lsipc>.

- Mostra informazioni su tutte le strutture IPC attive:

`lsipc`

- Mostra informazioni sui segmenti di [m]emoria condivisa attivi, [c]ode di messaggio o [s]emafori:

`lsipc {{--shmems|--queues|--semaphores}}`

- Mostra i dettagli completi sulla risorsa con un ID specifico:

`lsipc {{--shmems|--queues|--semaphores}} {{[-i|--id]}} {{resource_id}}`

- Stampa le colonne di output specificate (vedi tutte le colonne supportate con `--help`):

`lsipc {{[-o|--output]}} {{KEY,ID,PERMS,SEND,STATUS,NSEMS,RESOURCE,...}}`

- Usa formato [r]aw, [J]SON, [l]ist o [e]xport (key="value"):

`lsipc {{--raw|--json|--list|--export}}`

- Non troncare l'output:

`lsipc --notruncate`
