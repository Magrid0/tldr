# qm guest exec

> Esegue un comando specifico tramite un guest agent.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_guest_exec>.

- Esegue un comando specifico tramite un guest agent:

`qm {{[g|guest]}} exec {{100}} {{command}} {{argument1 argument2 ...}}`

- Esegue un comando specifico tramite un guest agent in modo asincrono:

`qm {{[g|guest]}} exec {{100}} {{argument1 argument2 ...}} --synchronous 0`

- Esegue un comando specifico tramite un guest agent con un timeout specificato di 10 secondi:

`qm {{[g|guest]}} exec {{100}} {{argument1 argument2...}} --timeout {{10}}`

- Esegue un comando specifico tramite un guest agent e inoltra l'input da `stdin` fino a EOF al guest agent:

`qm {{[g|guest]}} exec {{100}} {{argument1 argument2 ...}} --pass-stdin 1`
