# qm clone

> Crea una copia di una macchina virtuale su QEMU/KVM Virtual Machine Manager.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_clone>.

- Copia una macchina virtuale:

`qm clone {{100}} {{101}}`

- Copia una macchina virtuale usando un nome specifico:

`qm clone {{100}} {{101}} --name {{name}}`

- Copia una macchina virtuale usando una descrizione specifica:

`qm clone {{100}} {{101}} --description {{description}}`

- Copia una macchina virtuale creando una copia completa di tutti i dischi:

`qm clone {{100}} {{101}} --full`

- Copia una macchina virtuale usando un formato specifico per l'archiviazione dei file (richiede `--full`):

`qm clone {{100}} {{101}} --full --format {{qcow2|raw|vmdk}}`

- Copia una macchina virtuale e aggiungila a un pool specifico:

`qm clone {{100}} {{101}} --pool {{pool_name}}`
