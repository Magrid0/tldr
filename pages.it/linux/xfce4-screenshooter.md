# xfce4-screenshooter

> Lo strumento di screenshot XFCE4.
> Maggiori informazioni: <https://docs.xfce.org/apps/xfce4-screenshooter/start>.

- Avvia la GUI dello screenshooter:

`xfce4-screenshooter`

- Fai uno screenshot dell'intero schermo e avvia la GUI per chiedere come procedere:

`xfce4-screenshooter {{[-f|--fullscreen]}}`

- Fai uno screenshot dell'intero schermo e salvalo nella directory specificata:

`xfce4-screenshooter {{[-f|--fullscreen]}} {{[-s|--save]}} {{path/to/directory}}`

- Aspetta un po' di tempo prima di fare lo screenshot:

`xfce4-screenshooter {{[-d|--delay]}} {{secondi}}`

- Fai uno screenshot di una regione dello schermo (seleziona usando il mouse):

`xfce4-screenshooter {{[-r|--region]}}`

- Fai uno screenshot della finestra attiva e copialo negli appunti:

`xfce4-screenshooter {{[-w|--window]}} {{[-c|--clipboard]}}`

- Fai uno screenshot della finestra attiva e aprilo con un programma scelto:

`xfce4-screenshooter {{[-w|--window]}} {{[-o|--open]}} {{gimp}}`
