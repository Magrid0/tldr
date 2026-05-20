# mdadm

> Utility di gestione RAID.
> Maggiori informazioni: <https://manned.org/mdadm>.

- Crea array:

`sudo mdadm --create {{/dev/md/MyRAID}} --level {{raid_level}} --raid-devices {{number_of_disks}} {{/dev/sdXN}}`

- Ferma array:

`sudo mdadm --stop {{/dev/md0}}`

- Segna disco come guasto:

`sudo mdadm --fail {{/dev/md0}} {{/dev/sdXN}}`

- Rimuovi disco:

`sudo mdadm --remove {{/dev/md0}} {{/dev/sdXN}}`

- Aggiungi disco all'array:

`sudo mdadm --assemble {{/dev/md0}} {{/dev/sdXN}}`

- Mostra informazioni RAID:

`sudo mdadm --detail {{/dev/md0}}`

- Resetta disco cancellando i metadati RAID:

`sudo mdadm --zero-superblock {{/dev/sdXN}}`
