# qmrestore

> Ripristina i backup `vzdump` di QemuServer.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qmrestore.1.html>.

- Ripristina la macchina virtuale dal file di backup specificato sullo storage originale:

`qmrestore {{path/to/vzdump-qemu-100.vma.lzo}} {{100}}`

- Sovrascrive la macchina virtuale esistente da un file di backup specificato sullo storage originale:

`qmrestore {{path/to/vzdump-qemu-100.vma.lzo}} {{100}} --force true`

- Ripristina la macchina virtuale da un file di backup specificato su uno storage specifico:

`qmrestore {{path/to/vzdump-qemu-100.vma.lzo}} {{100}} --storage {{local}}`

- Avvia immediatamente la macchina virtuale dal backup mentre ripristina in background (solo su Proxmox Backup Server):

`qmrestore {{path/to/vzdump-qemu-100.vma.lzo}} {{100}} --live-restore true`
