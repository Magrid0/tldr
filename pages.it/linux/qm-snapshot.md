# qm snapshot

> Crea snapshot di macchine virtuali.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_snapshot>.

- Crea uno snapshot di una macchina virtuale specifica (il nome deve iniziare con una lettera):

`qm {{[sn|snapshot]}} {{100}} {{snapshot_name}}`

- Crea uno snapshot con una descrizione specifica:

`qm {{[sn|snapshot]}} {{100}} {{snapshot_name}} --description {{description}}`

- Crea uno snapshot includendo lo stato della VM:

`qm {{[sn|snapshot]}} {{100}} {{snapshot_name}} --description {{description}} --vmstate 1`

- Elenca gli snapshot di una VM:

`qm {{[lists|listsnapshot]}} {{100}}`

- Riporta lo stato di una VM specifica a uno snapshot specificato:

`qm {{[ro|rollback]}} {{100}} {{snap_name}}`
