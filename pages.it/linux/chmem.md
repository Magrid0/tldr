# chmem

> Modifica lo stato dei blocchi di memoria (online o offline) in un sistema Linux.
> Tipicamente utilizzato in ambienti virtualizzati per gestire l'hotplug della memoria.
> Maggiori informazioni: <https://manned.org/chmem>.

- Imposta un blocco di memoria offline:

`sudo chmem {{[-b|--block]}} {{[-d|--disable]}} {{block_number}}`

- Imposta un blocco di memoria online:

`sudo chmem {{[-b|--block]}} {{[-e|--enable]}} {{block_number}}`

- Imposta un intervallo di memoria offline utilizzando indirizzi esadecimali:

`sudo chmem {{[-d|--disable]}} 0x{{start_address}}-0x{{end_address}}`

- Imposta un intervallo di memoria online utilizzando indirizzi esadecimali:

`sudo chmem {{[-e|--enable]}} 0x{{start_address}}-0x{{end_address}}`

- Imposta la memoria online e la assegna a una zona specifica (ad es. Movable):

`sudo chmem {{[-e|--enable]}} 0x{{start_address}} {{[-z|--zone]}} {{Movable}}`

- Mostra aiuto:

`chmem {{[-h|--help]}}`
