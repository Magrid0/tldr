# qm sendkey

> Invia un evento di tasto di codifica QEMU monitor a una macchina virtuale.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_sendkey>.

- Invia l'evento di tasto specificato a una macchina virtuale specifica:

`qm {{[sen|sendkey]}} {{100}} {{key}}`

- Permette all'utente root di inviare un evento di tasto e ignorare i blocchi:

`qm {{[sen|sendkey]}} --skiplock {{true}} {{100}} {{key}}`
