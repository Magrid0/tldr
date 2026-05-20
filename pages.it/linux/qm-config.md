# qm config

> Mostra la configurazione della macchina virtuale con le modifiche in sospeso applicate.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_config>.

- Mostra la configurazione della macchina virtuale:

`qm {{[co|config]}} {{100}}`

- Mostra i valori di configurazione correnti invece dei valori in sospeso per la macchina virtuale:

`qm {{[co|config]}} --current {{true}} {{100}}`

- Recupera i valori di configurazione dallo snapshot specificato:

`qm {{[co|config]}} --snapshot {{snapshot_name}} {{100}}`
