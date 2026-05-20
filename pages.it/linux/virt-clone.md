# virt-clone

> Clona una macchina virtuale libvirt.
> Maggiori informazioni: <https://manned.org/virt-clone>.

- Clona una macchina virtuale e genera automaticamente un nuovo nome, percorso di archiviazione e indirizzo MAC:

`virt-clone {{[-o|--original]}} {{nome_vm}} --auto-clone`

- Clona una macchina virtuale e specifica il nuovo nome, percorso di archiviazione e indirizzo MAC:

`virt-clone {{[-o|--original]}} {{nome_vm}} {{[-n|--name]}} {{nuovo_nome_vm}} {{[-f|--file]}} {{percorso/della/nuova_archiviazione}} {{[-m|--mac]}} {{ff:ff:ff:ff:ff:ff|RANDOM}}`
