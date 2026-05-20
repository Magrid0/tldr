# xfs_admin

> Ottimizza un filesystem XFS.
> Maggiori informazioni: <https://manned.org/xfs_admin>.

- Mostra l'etichetta del filesystem:

`sudo xfs_admin {{[-l|--list]}} {{/dev/sdX}}`

- Imposta l'etichetta del filesystem:

`sudo xfs_admin {{[-L|--Label]}} "{{etichetta}}" {{/dev/sdX}}`

- Mostra l'UUID del filesystem:

`sudo xfs_admin {{[-u|--uuid]}} {{/dev/sdX}}`

- Imposta l'UUID del filesystem (usa con cautela):

`sudo xfs_admin {{[-U|--UUID]}} {{uuid}} {{/dev/sdX}}`

- Genera un nuovo UUID per il filesystem:

`sudo xfs_admin {{[-U|--UUID]}} generate {{/dev/sdX}}`

- Mostra aiuto:

`xfs_admin`
