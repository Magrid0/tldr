# mkinitcpio

> Genera ambienti ramdisk iniziali per l'avvio del kernel Linux basati sul/i preset specificato/i.
> Maggiori informazioni: <https://manned.org/mkinitcpio>.

- Esegue una prova a secco (mostra cosa verrebbe fatto senza effettivamente farlo):

`mkinitcpio`

- Genera ambienti ramdisk basati su tutti i preset esistenti (usato per rigenerare tutte le immagini initramfs dopo una modifica in `/etc/mkinitcpio.conf`):

`sudo mkinitcpio {{[-P|--allpresets]}}`

- Genera un ambiente ramdisk basato sul preset `linux`:

`sudo mkinitcpio {{[-p|--preset]}} linux`

- Genera un ambiente ramdisk basato sul preset `linux-lts`:

`sudo mkinitcpio {{[-p|--preset]}} linux-lts`

- Genera un'immagine initramfs usando un file di configurazione alternativo:

`sudo mkinitcpio {{[-c|--config]}} {{path/to/mkinitcpio.conf}} {{[-g|--generate]}} {{path/to/initramfs.img}}`

- Genera un'immagine initramfs per un kernel diverso da quello in esecuzione (le versioni del kernel installate si trovano in `/usr/lib/modules/`):

`sudo mkinitcpio {{[-k|--kernel]}} {{kernel_version}} {{[-g|--generate]}} {{path/to/initramfs.img}}`

- Elenca tutti gli hook disponibili:

`mkinitcpio {{[-L|--listhooks]}}`

- Mostra aiuto per un hook specifico:

`mkinitcpio {{[-H|--hookhelp]}} {{hook_name}}`
