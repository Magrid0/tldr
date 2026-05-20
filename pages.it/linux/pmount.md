# pmount

> Monta dispositivi hotpluggable arbitrari come utente normale.
> Maggiori informazioni: <https://manned.org/pmount>.

- Monta un dispositivo sotto `/media/` (usando il dispositivo come punto di mount):

`pmount {{/dev/del/dispositivo_a_blocchi}}`

- Monta un dispositivo con un tipo di filesystem specifico in `/media/etichetta`:

`pmount {{[-t|--type]}} {{filesystem}} {{/dev/del/dispositivo_a_blocchi}} {{etichetta}}`

- Monta un CD-ROM (tipo filesystem ISO9660) in modalità sola lettura:

`pmount {{[-t|--type]}} iso9660 {{[-r|--read-only]}} {{/dev/cdrom}}`

- Monta un disco formattato NTFS, forzando l'accesso in lettura-scrittura:

`pmount {{[-t|--type]}} ntfs {{[-w|--read-write]}} {{/dev/sdX}}`

- Mostra tutti i dispositivi rimovibili montati:

`pmount`
