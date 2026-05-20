# mhwd-kernel

> Gestisce e installa kernel Linux in Manjaro.
> Maggiori informazioni: <https://wiki.manjaro.org/index.php/Manjaro_Kernels>.

- Elenca tutti i kernel disponibili:

`mhwd-kernel {{[-l|--list]}}`

- Elenca tutti i kernel installati:

`mhwd-kernel {{[-li|--listinstalled]}}`

- Installa un kernel:

`sudo mhwd-kernel {{[-i|--install]}} {{kernel}}`

- Rimuove un kernel:

`sudo mhwd-kernel {{[-r|--remove]}} {{kernel}}`

- Installa un kernel, sostituendo quello attualmente in esecuzione:

`sudo mhwd-kernel {{[-i|--install]}} {{kernel}} rmc`
