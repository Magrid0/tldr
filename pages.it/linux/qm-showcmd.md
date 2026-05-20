# qm showcmd

> Mostra la riga di comando usata per avviare la VM (info di debug).
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_showcmd>.

- Mostra la riga di comando per una macchina virtuale specifica:

`qm {{[sho|showcmd]}} {{100}}`

- Mette ogni opzione su una nuova riga per migliorare la leggibilità:

`qm {{[sho|showcmd]}} {{100}} --pretty {{true}}`

- Recupera i valori di configurazione da uno snapshot specifico:

`qm {{[sho|showcmd]}} {{100}} --snapshot {{string}}`
