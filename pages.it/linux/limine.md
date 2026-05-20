# limine

> Un bootloader avanzato, portatile e multiprotocollo.
> Vedi anche: `limine-enroll-config`, `limine-entry-tool`, `limine-snapper-sync`.
> Maggiori informazioni: <https://codeberg.org/Limine/Limine>.

- Installa Limine su un disco con partizione MBR:

`limine bios-install {{/dev/sdX}}`

- Installa Limine su un disco con partizione GPT con una specifica partizione di avvio BIOS:

`limine bios-install {{/dev/sdX}} {{partition_number}}`

- Installa Limine su un file immagine disco:

`limine bios-install {{path/to/image.iso}}`

- Installa Limine per sistemi UEFI moderni (richiede il pacchetto `limine-entry-tool`):

`limine-install`

- Aggiorna le voci di avvio dopo un aggiornamento del kernel (richiede il pacchetto `limine-entry-tool`):

`limine-update`

- Cerca altri sistemi operativi da aggiungere al menu di avvio (richiede il pacchetto `limine-entry-tool`):

`limine-scan`
