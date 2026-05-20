# vgscan

> Cerca volume group su tutti i dispositivi a blocchi Logical Volume Manager (LVM) supportati.
> Vedi anche: `lvm`, `vgchange`.
> Maggiori informazioni: <https://manned.org/vgscan>.

- Cerca volume group e stampa le informazioni su ogni gruppo trovato:

`sudo vgscan`

- Cerca volume group e aggiunge i file speciali in `/dev`, se non esistono già, necessari per accedere ai volumi logici nei gruppi trovati:

`sudo vgscan --mknodes`
