# hwinfo

> Sonda l'hardware presente nel sistema.
> Vedi anche: `inxi`, `lshw`, `dmidecode`.
> Maggiori informazioni: <https://manpages.opensuse.org/hwinfo/hwinfo.8.en.html>.

- Mostra tutte le informazioni hardware disponibili:

`hwinfo`

- Mostra informazioni su un componente hardware specifico:

`hwinfo --{{cpu|memory|disk|gfxcard|network|usb|pci|keyboard|mouse|monitor|sound|fingerprint|...}}`

- Mostra informazioni su un componente hardware specifico in modo sintetico:

`hwinfo {{--component}} --short`

- Scrive tutte le informazioni hardware in un file:

`hwinfo --all --log {{path/to/file}}`

- Mostra aiuto:

`hwinfo --help`
