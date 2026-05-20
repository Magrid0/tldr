# dmidecode

> Mostra i contenuti della tabella DMI (anche conosciuta come SMBIOS) in formato leggibile.
> Vedi anche: `inxi`, `lshw`, `hwinfo`.
> Maggiori informazioni: <https://manned.org/dmidecode>.

- Mostra tutti i contenuti della tabella DMI:

`sudo dmidecode`

- Mostra la versione del BIOS:

`sudo dmidecode {{[-s|--string]}} bios-version`

- Mostra il numero di serie del sistema:

`sudo dmidecode {{[-s|--string]}} system-serial-number`

- Mostra le informazioni del BIOS:

`sudo dmidecode {{[-t|--type]}} bios`

- Mostra le informazioni della CPU:

`sudo dmidecode {{[-t|--type]}} processor`

- Mostra le informazioni della memoria:

`sudo dmidecode {{[-t|--type]}} memory`
