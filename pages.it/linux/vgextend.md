# vgextend

> Aggiunge uno o più volumi fisici a un volume group esistente.
> Maggiori informazioni: <https://manned.org/vgextend>.

- Aggiunge un volume fisico a un volume group esistente:

`sudo vgextend {{vg1}} {{/dev/sda1}}`

- Aggiunge più volumi fisici a un volume group esistente:

`sudo vgextend {{vg1}} {{/dev/sda1 /dev/sda2 ...}}`
