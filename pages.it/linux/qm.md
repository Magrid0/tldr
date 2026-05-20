# qm

> QEMU/KVM Virtual Machine Manager.
> Alcuni sottocomandi come `list`, `start`, `stop`, `clone`, ecc. hanno la propria documentazione d'uso.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Elenca tutte le macchine virtuali:

`qm list`

- Crea una macchina virtuale con un disco SCSI da 4 GB sullo storage `local-lvm` e un ID di 100 usando un file ISO caricato sullo storage locale:

`qm {{[cr|create]}} {{100}} --scsi0 {{local-lvm:4}} --net0 {{e1000}} --cdrom {{local:iso/proxmox-mailgateway_2.1.iso}}`

- Mostra la configurazione di una macchina virtuale, specificando il suo ID:

`qm {{[co|config]}} {{100}}`

- Avvia una macchina virtuale specifica:

`qm start {{100}}`

- Invia una richiesta di spegnimento, poi aspetta fino a quando la macchina virtuale è ferma:

`qm {{[shu|shutdown]}} {{100}} && qm {{[w|wait]}} {{100}}`

- Distrugge una macchina virtuale e rimuove tutte le risorse correlate:

`qm {{[des|destroy]}} {{100}} --purge`
