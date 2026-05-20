# qm reboot

> Riavvia una macchina virtuale spegnendola e riavviandola dopo aver applicato le modifiche in sospeso.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_reboot>.

- Riavvia una macchina virtuale:

`qm {{[reb|reboot]}} {{100}}`

- Riavvia una macchina virtuale dopo aver aspettato al massimo 10 secondi:

`qm {{[reb|reboot]}} {{100}} --timeout {{10}}`
