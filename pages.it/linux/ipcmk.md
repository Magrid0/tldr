# ipcmk

> Crea risorse IPC (Inter-process Communication).
> Maggiori informazioni: <https://manned.org/ipcmk>.

- Crea un segmento di memoria condivisa:

`ipcmk {{[-M|--shmem]}} {{segment_size_in_bytes}}`

- Crea un semaforo:

`ipcmk {{[-S|--semaphore]}} {{element_size}}`

- Crea una coda di messaggi:

`ipcmk {{[-Q|--queue]}}`

- Crea un segmento di memoria condivisa con permessi specifici (il default è 0644):

`ipcmk {{[-M|--shmem]}} {{segment_size_in_bytes}} {{octal_permissions}}`
