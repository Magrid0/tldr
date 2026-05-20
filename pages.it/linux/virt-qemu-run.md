# virt-qemu-run

> Strumento sperimentale per eseguire una VM guest QEMU indipendentemente da `libvirtd`.
> Maggiori informazioni: <https://libvirt.org/manpages/virt-qemu-run.html>.

- Esegue una macchina virtuale QEMU:

`virt-qemu-run {{percorso/del/guest.xml}}`

- Esegue una macchina virtuale QEMU e salva lo stato in una directory specifica:

`virt-qemu-run {{[-r|--root]}} {{percorso/della/directory}} {{percorso/del/guest.xml}}`

- Esegue una macchina virtuale QEMU e mostra informazioni dettagliate sull'avvio:

`virt-qemu-run {{[-v|--verbose]}} {{percorso/del/guest.xml}}`

- Mostra aiuto:

`virt-qemu-run {{[-h|--help]}}`
