# mkswap

> Imposta un'area di swap Linux su un dispositivo o in un file.
> Nota: `path/to/file` può riferirsi a un file regolare o a una partizione di swap.
> Maggiori informazioni: <https://manned.org/mkswap>.

- Imposta un'area di swap specifica:

`sudo mkswap {{path/to/file}}`

- Controlla la presenza di blocchi danneggiati in una partizione prima di creare l'area di swap:

`sudo mkswap {{[-c|--check]}} {{path/to/file}}`

- Specifica un'etichetta per la partizione (per permettere a `swapon` di usare l'etichetta):

`sudo mkswap {{[-L|--label]}} {{label}} {{/dev/sdXY}}`

- Usa l'UUID specificato:

`sudo mkswap {{[-U|--uuid]}} {{clear|random|time|uuid_value}}`

- Imposta un file di swap (per btrfs, vedi `tldr btrfs filesystem` invece):

`sudo mkswap {{[-s|--size]}} {{file_size}} {{[-F|--file]}} {{path/to/swapfile}}`
