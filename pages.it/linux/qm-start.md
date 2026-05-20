# qm start

> Avvia una macchina virtuale su QEMU/KVM Virtual Machine Manager.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_start>.

- Avvia una macchina virtuale specifica:

`qm start {{100}}`

- Specifica il tipo di macchina QEMU (cioè la CPU da emulare):

`qm start {{100}} --machine {{q35}}`

- Avvia una macchina virtuale specifica con un timeout di 60 secondi:

`qm start {{100}} --timeout {{60}}`
