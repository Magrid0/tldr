# vgcreate

> Crea volume group combinando più dispositivi di memorizzazione di massa.
> Vedi anche: `lvm`.
> Maggiori informazioni: <https://manned.org/vgcreate>.

- Crea un nuovo volume group usando il dispositivo specificato:

`sudo vgcreate {{volume_group}} {{/dev/sdXY}}`

- Crea un nuovo volume group usando più dispositivi:

`sudo vgcreate {{volume_group}} {{/dev/sdXY}} {{/dev/sdXZ}}`
