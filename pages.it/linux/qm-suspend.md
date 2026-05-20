# qm suspend

> Sospende una macchina virtuale (VM) in Proxmox Virtual Environment (PVE).
> Usa i flag `--skiplock` e `--skiplockstorage` con cautela, poiché possono portare alla corruzione dei dati in determinate situazioni.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_suspend>.

- Sospende una macchina virtuale tramite ID:

`qm {{[su|suspend]}} {{100}} {{integer}}`

- Salta il controllo del blocco durante la sospensione della VM:

`qm {{[su|suspend]}} {{100}} {{integer}} --skiplock`

- Salta il controllo del blocco per lo storage durante la sospensione della VM:

`qm {{[su|suspend]}} {{100}} {{integer}} --skiplockstorage`
