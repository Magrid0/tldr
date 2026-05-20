# virt-install

> Crea macchine virtuali con libvirt e avvia l'installazione del sistema operativo.
> Nota: Potrebbe essere necessario passare `--connect URI` ai comandi o configurare l'URI in `$XDG_CONFIG_HOME/libvirt/libvirt.conf`.
> Maggiori informazioni: <https://manned.org/virt-install>.

- Crea una macchina virtuale con 1 GB di RAM e 12 GB di archiviazione e avvia un'installazione di Debian:

`virt-install {{[-n|--name]}} {{nome_vm}} --memory {{1024}} --disk path={{percorso/dell/immagine.qcow2}},size={{12}} {{[-c|--cdrom]}} {{percorso/di/debian.iso}}`

- Crea una macchina virtuale x86-64, accelerata KVM, basata su UEFI con chipset Q35, 4 GiB di RAM, 16 GiB di archiviazione RAW e avvia un'installazione di Fedora:

`virt-install {{[-n|--name]}} {{nome_vm}} --arch {{x86_64}} --virt-type {{kvm}} --machine {{q35}} --boot {{uefi}} --memory {{4096}} --disk path={{percorso/dell/immagine.raw}},size={{16}} {{[-c|--cdrom]}} {{percorso/di/fedora.iso}}`

- Crea una macchina virtuale live senza disco, senza dispositivo audio emulato o controller USB. Non avviare un'installazione e non connetterti automaticamente alla console, ma collega un cdrom (utile quando si usa un CD live come Tails):

`virt-install {{[-n|--name]}} {{nome_vm}} --memory {{512}} --disk {{none}} --controller {{type=usb,model=none}} --sound {{none}} --autoconsole {{none}} --install {{no_install=yes}} {{[-c|--cdrom]}} {{percorso/di/tails.iso}}`

- Crea una macchina virtuale con 16 GiB di RAM, 250 GiB di archiviazione, 8 core con hyperthreading, una topologia CPU specifica e un modello CPU che condivide la maggior parte delle funzionalità con la CPU host:

`virt-install {{[-n|--name]}} {{nome_vm}} --cpu {{host-model}},topology.sockets={{1}},topology.cores={{4}},topology.threads={{2}} --memory {{16384}} --disk path={{percorso/dell/immagine.qcow2}},size={{250}} {{[-c|--cdrom]}} {{percorso/di/debian.iso}}`

- Crea una macchina virtuale e avvia un deployment automatizzato basato su Fedora 43 usando solo risorse remote (nessun ISO richiesto):

`virt-install {{[-n|--name]}} {{nome_vm}} --memory {{2048}} --disk path={{percorso/dell/immagine.qcow2}},size={{20}} {{[-l|--location]}} {{https://download.fedoraproject.org/pub/fedora/linux/releases/43/Everything/x86_64/os/}} {{[-x|--extra-args]}} "{{inst.ks=https://example.com/path/to/kickstart.ks}}"`
