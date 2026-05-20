# lvscan

> Scansiona (elenca) tutti i volumi logici nel sistema.
> Parte della suite LVM (Logical Volume Manager).
> Maggiori informazioni: <https://manned.org/lvscan>.

- Elenca tutti i volumi logici:

`sudo lvscan`

- Elenca solo i volumi logici attivi:

`sudo lvscan --active`

- Elenca solo i volumi logici inattivi:

`sudo lvscan --inactive`

- Mostra i volumi logici in formato JSON:

`sudo lvscan --reportformat json`
