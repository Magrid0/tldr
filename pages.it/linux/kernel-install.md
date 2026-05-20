# kernel-install

> Aggiunge e rimuove immagini kernel e initrd da `/boot`.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/kernel-install.html>.

- Mostra la configurazione corrente del kernel che è stata configurata o rilevata automaticamente:

`kernel-install`

- Mostra la configurazione per un'immagine kernel specifica:

`kernel-install inspect {{path/to/kernel_image}}`

- Aggiunge un kernel alla partizione del bootloader:

`sudo kernel-install add {{kernel_version}} {{path/to/kernel_image}}`

- Aggiunge un kernel e immagini initramfs alla partizione del bootloader:

`sudo kernel-install add {{kernel_version}} {{path/to/kernel_image}} {{path/to/initrd1 path/to/initrd2 ...}}`

- Rimuove un kernel dalla partizione del bootloader:

`sudo kernel-install remove {{kernel_version}}`
