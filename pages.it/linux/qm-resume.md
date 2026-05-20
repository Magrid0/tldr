# qm resume

> Riprende una macchina virtuale.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_resume>.

- Riprende una macchina virtuale specifica:

`qm {{[resu|resume]}} {{100}}`

- Riprende una macchina virtuale specifica ignorando i blocchi (richiede root):

`sudo qm {{[resu|resume]}} {{100}} --skiplock true`
