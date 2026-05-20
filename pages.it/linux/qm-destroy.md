# qm destroy

> Distrugge una macchina virtuale su QEMU/KVM Virtual Machine Manager.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_destroy>.

- Distrugge una macchina virtuale specifica:

`qm {{[des|destroy]}} {{100}}`

- Distrugge tutti i dischi che non sono esplicitamente referenziati nella configurazione di una macchina virtuale specifica:

`qm {{[des|destroy]}} {{100}} --destroy-unreferenced-disks`

- Distrugge una macchina virtuale e la rimuove da tutte le posizioni (inventario, backup, high availability, ecc.):

`qm {{[des|destroy]}} {{100}} --purge`

- Distrugge una macchina virtuale specifica ignorando i blocchi e forzando la distruzione:

`sudo qm {{[des|destroy]}} {{100}} --skiplock`
