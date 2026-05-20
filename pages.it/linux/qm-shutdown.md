# qm shutdown

> Spegne una macchina virtuale su QEMU/KVM Virtual Machine Manager.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_shutdown>.

- Spegne una macchina virtuale:

`qm {{[shu|shutdown]}} {{100}}`

- Spegne una macchina virtuale dopo aver aspettato al massimo 10 secondi:

`qm {{[shu|shutdown]}} {{100}} --timeout {{10}}`

- Spegne una macchina virtuale e non disattiva i volumi di storage:

`qm {{[shu|shutdown]}} {{100}} --keepActive {{true}}`

- Spegne una macchina virtuale e salta il blocco (solo root può usare questa opzione):

`qm {{[shu|shutdown]}} {{100}} --skiplock {{true}}`

- Ferma e spegne una macchina virtuale:

`qm {{[shu|shutdown]}} {{100}} --forceStop {{true}}`
