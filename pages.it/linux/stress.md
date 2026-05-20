# stress

> Test di stress per CPU, memoria e IO su un sistema Linux.
> Maggiori informazioni: <https://manned.org/stress>.

- Crea 4 worker per testare lo stress della CPU:

`stress {{[-c|--cpu]}} {{4}}`

- Crea 2 worker per testare lo stress dell'IO e termina dopo 5 secondi:

`stress {{[-i|--io]}} {{2}} {{[-t|--timeout]}} {{5}}`

- Crea 2 worker per testare lo stress della memoria (ogni worker alloca 256M byte):

`stress {{[-m|--vm]}} {{2}} --vm-bytes {{256M}}`

- Crea 2 worker che eseguono write()/unlink() (ogni worker scrive 1G byte):

`stress {{[-d|--hdd]}} {{2}} --hdd-bytes {{1GB}}`
