# qm wait

> Aspetta fino a quando la macchina virtuale è ferma.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_wait>.

- Aspetta fino a quando la macchina virtuale è ferma:

`qm {{[w|wait]}} {{100}}`

- Aspetta fino a quando la macchina virtuale è ferma con un timeout di 10 secondi:

`qm {{[w|wait]}} {{100}} --timeout {{10}}`

- Invia una richiesta di spegnimento, poi aspetta fino a quando la macchina virtuale è ferma con un timeout di 10 secondi:

`qm {{[shu|shutdown]}} {{100}} && qm {{[w|wait]}} {{100}} --timeout {{10}}`
