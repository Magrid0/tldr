# gpm

> Abilita il supporto del mouse per la console virtuale Linux.
> Maggiori informazioni: <https://manned.org/gpm>.

- Avvia gpm con un mouse PS/2 di tipo ps2:

`sudo gpm -m /dev/input/mice -t ps2`

- Avvia gpm con un mouse seriale Microsoft di tipo ms:

`sudo gpm -m /dev/ttyS0 -t ms`

- Avvia gpm con un mouse e tipo in primo piano per il debug:

`sudo gpm -m {{path/to/mouse_device}} -t {{mouse_type}} -D`

- Termina il gpm in esecuzione:

`sudo gpm -k`

- Avvia gpm con un mouse e tipo in modalità ripetitore per la compatibilità con X server:

`sudo gpm -m {{path/to/mouse_device}} -t {{mouse_type}} -R`

- Elenca i tipi di mouse disponibili:

`gpm -t help`
