# qm cleanup

> Pulisce le risorse su QEMU/KVM Virtual Machine Manager come dispositivi tap, VGPU, ecc.
> Chiamato dopo che una VM si spegne, crasha, ecc.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_cleanup>.

- Pulisce le risorse:

`qm {{[cl|cleanup]}} {{100}} {{clean-shutdown}} {{guest-requested}}`
