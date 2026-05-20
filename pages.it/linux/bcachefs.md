# bcachefs

> Gestisce filesystem/dispositivi `bcachefs`.
> Alcuni sottocomandi come `device` hanno la propria documentazione d'uso.
> Maggiori informazioni: <https://bcachefs-docs.readthedocs.io/en/latest/index.html>.

- Formatta una partizione con `bcachefs`:

`sudo bcachefs format {{path/to/partition}}`

- Monta un filesystem `bcachefs`:

`sudo bcachefs mount {{path/to/partition}} {{path/to/mountpoint}}`

- Crea un filesystem RAID 0 dove un SSD funge da cache e un HDD funge da archiviazione a lungo termine:

`sudo bcachefs format {{[-l|--label]}} {{ssd.ssd1}} {{path/to/ssd_partition}} {{[-l|--label]}} {{hdd.hdd1}} {{path/to/hdd_partition}} --replicas 1 --foreground_target {{ssd}} --promote_target {{ssd}} --background_target {{hdd}}`

- Monta un filesystem multidispositivo:

`sudo bcachefs mount {{path/to/partition1}}:{{path/to/partition2}} {{path/to/mountpoint}}`

- Mostra l'utilizzo del disco:

`bcachefs fs usage {{[-h|--human-readable]}} {{path/to/mountpoint}}`

- Imposta le repliche dopo la formattazione e il montaggio:

`sudo bcachefs set-fs-option --metadata_replicas {{2}} --data_replicas {{2}} {{path/to/partition}}`

- Forza `bcachefs` ad assicurarsi che tutti i file siano replicati:

`sudo bcachefs data rereplicate {{path/to/mountpoint}}`

- Crea un'istantanea di una directory specifica:

`bcachefs subvolume snapshot {{path/to/directory}} {{path/to/snapshot}}`
