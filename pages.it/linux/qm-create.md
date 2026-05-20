# qm create

> Crea o ripristina una macchina virtuale su QEMU/KVM Virtual Machine Manager.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_create>.

- Crea una macchina virtuale con accesso a 512 MiB di memoria e 1 core CPU:

`qm {{[cr|create]}} {{100}}`

- Assegna un nome alla macchina virtuale e avvia automaticamente la macchina dopo la creazione:

`qm {{[cr|create]}} {{100}} --name {{vm_name}} --start`

- Assegna a una macchina virtuale una quantità specificata di memoria e CPU:

`qm {{[cr|create]}} {{100}} --memory {{8192}} --cores {{4}}`

- Specifica il tipo di sistema operativo sulla macchina:

`qm {{[cr|create]}} {{100}} --ostype {{win10}}`

- Sostituisce una macchina esistente (richiede l'archiviazione):

`qm {{[cr|create]}} {{100}} --archive {{path/to/backup_file.tar}} --force 1`

- Specifica uno script eseguito automaticamente in base allo stato della macchina virtuale:

`qm {{[cr|create]}} {{100}} --hookscript {{path/to/script.pl}}`

- Specifica il supporto di installazione:

`qm {{[cr|create]}} {{100}} --cdrom {{local:iso/install-media.iso}}`

- Crea una VM che si collega in bridge alla rete host:

`qm {{[cr|create]}} {{100}} --net{{0}} virtio,bridge=vmbr{{0}}`
