# qm set

> Imposta le opzioni della macchina virtuale.
> Maggiori informazioni: <https://pve.proxmox.com/pve-docs/qm.1.html#cli_qm_set>.

- Imposta un nome per una VM nella GUI:

`qm set {{100}} --name {{vm_name}}`

- Imposta una VM per l'avvio automatico all'accensione:

`qm set {{100}} --autostart {{0|1}}`

- Imposta il numero di core assegnati a una VM:

`qm set {{100}} --cores {{4}}`

- Imposta la quantità di memoria assegnata:

`qm set {{100}} --memory {{8192}}`

- Assegna a una VM un dispositivo di rete e la collega in bridge alla rete host:

`qm set {{100}} --net{{0}} {{virtio|e1000|rtl8139|vmxnet3}},bridge=vmbr{{0}}`

- Elimina un dispositivo:

`qm set {{100}} --delete {{device_name0,device_name1,...}}`

- Passa un dispositivo GPU al guest:

`qm set {{100}} --hostpci{{0}} {{0000:00:02}},x-vga=1 --bios ovmf`
