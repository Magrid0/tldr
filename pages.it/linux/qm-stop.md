# qm stop

> Ferma una macchina virtuale.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_stop>.

- Ferma una macchina virtuale immediatamente:

`qm stop {{100}}`

- Ferma una macchina virtuale e aspetta al massimo 10 secondi:

`qm stop {{100}} --timeout {{10}}`

- Ferma una macchina virtuale e salta il blocco (solo root può usare questa opzione):

`qm stop {{100}} --skiplock {{true}}`

- Ferma una macchina virtuale e non disattivare i volumi di storage:

`qm stop {{100}} --keepActive {{true}}`
