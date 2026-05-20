# pvscan

> Elenca tutti i volumi fisici e gestisce il loro stato online.
> Maggiori informazioni: <https://manned.org/pvscan>.

- Elenca tutti i volumi fisici:

`sudo pvscan`

- Mostra il volume group che utilizza un volume fisico specifico:

`sudo pvscan --cache --listvg {{/dev/sdX}}`

- Mostra i volumi logici che utilizzano un volume fisico specifico:

`sudo pvscan --cache --listlvs {{/dev/sdX}}`

- Mostra informazioni dettagliate in formato JSON:

`sudo pvscan --reportformat json`
