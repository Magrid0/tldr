# mkfs.btrfs

> Crea un filesystem BTRFS.
> L'impostazione predefinita è `raid1`, che specifica 2 copie di un blocco di dati distribuite su 2 dispositivi diversi.
> Maggiori informazioni: <https://btrfs.readthedocs.io/en/latest/mkfs.btrfs.html>.

- Crea un filesystem Btrfs su una partizione vuota:

`sudo mkfs.btrfs {{/dev/sdXY}}`

- Crea un filesystem btrfs su un singolo dispositivo:

`sudo mkfs.btrfs {{[-m|--metadata]}} single {{[-d|--data]}} single {{/dev/sdX}}`

- Crea un filesystem btrfs su più dispositivi con raid1:

`sudo mkfs.btrfs {{[-m|--metadata]}} raid1 {{[-d|--data]}} raid1 {{/dev/sdX /dev/sdY /dev/sdZ ...}}`

- Imposta un'etichetta per il filesystem:

`sudo mkfs.btrfs {{[-L|--label]}} "{{label}}" {{/dev/sdX /dev/sdY ...}}`

- Sovrascrive il filesystem esistente se rilevato:

`sudo mkfs.btrfs {{[-f|--force]}} {{/dev/sdX}}`
