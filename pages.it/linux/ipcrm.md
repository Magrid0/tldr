# ipcrm

> Elimina risorse IPC (Inter-process Communication).
> Maggiori informazioni: <https://manned.org/ipcrm>.

- Elimina un segmento di memoria condivisa per ID:

`ipcrm {{[-m|--shmem-id]}} {{shmem_id}}`

- Elimina un segmento di memoria condivisa per chiave:

`ipcrm {{[-M|--shmem-key]}} {{shmem_key}}`

- Elimina una coda IPC per ID:

`ipcrm {{[-q|--queue-id]}} {{ipc_queue_id}}`

- Elimina una coda IPC per chiave:

`ipcrm {{[-Q|--queue-key]}} {{ipc_queue_key}}`

- Elimina un semaforo per ID:

`ipcrm {{[-s|--semaphore-id]}} {{semaphore_id}}`

- Elimina un semaforo per chiave:

`ipcrm {{[-S|--semaphore-key]}} {{semaphore_key}}`

- Elimina tutte le risorse IPC:

`ipcrm {{[-a|--all]}}`
