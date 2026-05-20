# udisksctl

> Interagisci con `udisksd` per interrogare e manipolare i dispositivi di archiviazione.
> Vedi anche: `mount`.
> Maggiori informazioni: <https://storaged.org/doc/udisks2-api/latest/udisksctl.1.html>.

- Mostra informazioni di alto livello su unità disco e dispositivi a blocchi:

`udisksctl status`

- Mostra informazioni dettagliate su un dispositivo:

`udisksctl info {{[-b|--block-device]}} {{/dev/sdX}}`

- Mostra informazioni dettagliate su una partizione del dispositivo:

`udisksctl info {{[-b|--block-device]}} {{/dev/sdXN}}`

- Monta una partizione del dispositivo e stampa il punto di montaggio:

`udisksctl mount {{[-b|--block-device]}} {{/dev/sdXN}}`

- Smonta una partizione del dispositivo:

`udisksctl unmount {{[-b|--block-device]}} {{/dev/sdXN}}`

- Spegni un dispositivo per rimuoverlo in sicurezza:

`udisksctl power-off {{[-b|--block-device]}} {{/dev/sdX}}`

- Monitora il demone per eventi:

`udisksctl monitor`
