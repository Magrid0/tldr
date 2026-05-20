# qm guest

> Gestisce un guest agent di una VM.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_guest_cmd>.

- Stampa lo stato di un PID specifico:

`qm {{[g|guest]}} {{[exec-s|exec-status]}} {{100}} {{pid}}`

- Imposta una password per un utente specifico in una macchina virtuale in modo interattivo:

`qm {{[g|guest]}} {{[p|passwd]}} {{100}} {{username}}`

- Imposta una password già hashata per un utente specifico in una macchina virtuale in modo interattivo:

`qm {{[g|guest]}} {{[p|passwd]}} {{100}} {{username}} --crypted 1`

- Esegue un comando QEMU Guest Agent specifico:

`qm {{[g|guest]}} {{[c|cmd]}} {{100}} {{fsfreeze-freeze|fsfreeze-status|fsfreeze-thaw|fstrim|get-fsinfo|...}}`

- Esegue un comando specifico tramite un guest agent:

`qm {{[g|guest]}} exec {{100}} {{command}} {{argument1 argument2 ...}}`

- Esegue un comando specifico tramite un guest agent in modo asincrono:

`qm {{[g|guest]}} exec {{100}} {{argument1 argument2 ...}} --synchronous 0`

- Esegue un comando specifico tramite un guest agent con un timeout specificato di 10 secondi:

`qm {{[g|guest]}} exec {{100}} {{argument1 argument2...}} --timeout {{10}}`

- Esegue un comando specifico tramite un guest agent e inoltra l'input da `stdin` fino a EOF al guest agent:

`qm {{[g|guest]}} exec {{100}} {{argument1 argument2 ...}} --pass-stdin 1`
