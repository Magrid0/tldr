# lvcreate

> Crea un volume logico in un gruppo di volumi esistente. Un gruppo di volumi è una raccolta di volumi logici e fisici.
> Vedi anche: `lvm`.
> Maggiori informazioni: <https://manned.org/lvcreate>.

- Crea un volume logico di 10 gigabyte nel gruppo di volumi `vg1`:

`sudo lvcreate {{[-L|--size]}} 10G vg1`

- Crea un volume logico lineare di 1500 megabyte chiamato `mylv` nel gruppo di volumi `vg1`:

`sudo lvcreate {{[-L|--size]}} 1500 {{[-n|--name]}} mylv vg1`

- Crea un volume logico chiamato `mylv` che usa il 60% dello spazio totale nel gruppo di volumi `vg1`:

`sudo lvcreate {{[-l|--extents]}} 60%VG {{[-n|--name]}} mylv vg1`

- Crea un volume logico chiamato `mylv` che usa tutto lo spazio non allocato nel gruppo di volumi `vg1`:

`sudo lvcreate {{[-l|--extents]}} 100%FREE {{[-n|--name]}} mylv vg1`
