# eject

> Espelle CD, floppy disk, unità a nastro e chiavette USB.
> Maggiori informazioni: <https://manned.org/eject>.

- Mostra il dispositivo predefinito:

`eject {{[-d|--default]}}`

- Espelle il dispositivo predefinito:

`eject`

- Espelle un dispositivo specifico (l'ordine predefinito è cd-rom, scsi, floppy e nastro):

`eject {{/dev/cdrom}}`

- Commuta se il vassoio di un dispositivo è aperto o chiuso:

`eject {{[-T|--traytoggle]}} {{/dev/cdrom}}`

- Espelle un'unità CD:

`eject {{[-r|--cdrom]}} {{/dev/cdrom}}`

- Espelle un'unità floppy:

`eject {{[-f|--floppy]}} {{/mnt/floppy}}`

- Espelle un'unità a nastro:

`eject {{[-q|--tape]}} {{/mnt/tape}}`

- Imposta se il pulsante di espulsione fisico deve essere [i]gnorato (`on` impedisce l'espulsione):

`eject {{[-i|--manualeject]}} {{on|off}}`
