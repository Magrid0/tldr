# qm reset

> Resetta una macchina virtuale su QEMU/KVM Virtual Machine Manager.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_reset>.

- Resetta una macchina virtuale:

`qm reset {{100}}`

- Resetta una macchina virtuale e salta il blocco (solo root può usare questa opzione):

`qm reset {{100}} --skiplock {{true}}`
