# efibootmgr

> Manipola il gestore di avvio UEFI.
> Maggiori informazioni: <https://manned.org/efibootmgr>.

- Elenca tutte le opzioni di avvio con i loro numeri:

`efibootmgr {{[-u|--unicode]}}`

- Aggiunge UEFI Shell v2 come opzione di avvio:

`sudo efibootmgr {{[-c|--create]}} {{[-d|--disk]}} {{/dev/sda}} {{[-p|--part]}} {{1}} {{[-l|--loader]}} "{{\path\to\shell.efi}}" {{[-L|--label]}} "{{UEFI Shell}}"`

- Aggiunge Linux come opzione di avvio:

`sudo efibootmgr {{[-c|--create]}} {{[-d|--disk]}} {{/dev/sda}} {{[-p|--part]}} {{1}} {{[-l|--loader]}} "{{\vmlinuz}}" {{[-u|--unicode]}} "{{kernel_cmdline}}" {{[-L|--label]}} "{{Linux}}"`

- Cambia l'ordine di avvio corrente:

`sudo efibootmgr {{[-o|--bootorder]}} {{0002,0008,0001,001A,...}}`

- Elimina un'opzione di avvio:

`sudo efibootmgr {{[-b|--bootnum]}} {{0008}} {{[-B|--delete-bootnum]}}`
