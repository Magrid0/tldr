# limine-entry-tool

> Uno script helper per gestire le voci del bootloader Limine su sistemi UEFI.
> Maggiori informazioni: <https://gitlab.com/Zesko/limine-entry-tool>.

- Cerca altre voci di avvio UEFI attive e le aggiunge al menu Limine:

`limine-entry-tool --scan`

- Aggiunge una nuova voce di avvio del kernel con initramfs e file kernel:

`limine-entry-tool --add "{{kernel_name}}" "{{path/to/initramfs}}" "{{path/to/vmlinuz}}"`

- Aggiunge una nuova voce di avvio dell'immagine del kernel unificata (UKI):

`limine-entry-tool --add-uki "{{kernel_name}}" "{{path/to/uki.efi}}"`

- Rimuove una voce di avvio del kernel e i suoi file associati dall'ESP:

`limine-entry-tool --remove "{{kernel_name}}"`

- Rimuove un'intera voce di sistema operativo per nome o ID macchina:

`limine-entry-tool --remove-os "{{os_name|machine_id}}"`

- Aggiunge una voce di avvio EFI per un bootloader alternativo (es. Windows):

`limine-entry-tool --add-efi "{{efi_entry_name}}" "{{path/to/loader.efi}}"`
