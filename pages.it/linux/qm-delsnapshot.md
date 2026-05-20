# qm delsnapshot

> Elimina snapshot di macchine virtuali.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_delsnapshot>.

- Elimina uno snapshot:

`qm {{[del|delsnapshot]}} {{100}} {{snapshot_name}}`

- Elimina uno snapshot da un file di configurazione (anche se la rimozione dello snapshot del disco fallisce):

`qm {{[del|delsnapshot]}} {{100}} {{snapshot_name}} --force 1`
