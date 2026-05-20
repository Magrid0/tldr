# vgchange

> Modifica gli attributi di un volume group di Logical Volume Manager (LVM).
> Vedi anche: `lvm`.
> Maggiori informazioni: <https://manned.org/vgchange>.

- Modifica lo stato di attivazione dei volumi logici in tutti i volume group:

`sudo vgchange {{[-a|--activate]}} {{y|n}}`

- Modifica lo stato di attivazione dei volumi logici nel volume group specificato (determinato con `vgscan`):

`sudo vgchange {{[-a|--activate]}} {{y|n}} {{volume_group}}`
