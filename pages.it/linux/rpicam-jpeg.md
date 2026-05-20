# rpicam-jpeg

> Cattura e salva un'immagine JPEG usando una fotocamera Raspberry Pi.
> Maggiori informazioni: <https://www.raspberrypi.com/documentation/computers/camera_software.html#rpicam-jpeg>.

- Cattura un'immagine e nomina il file:

`rpicam-jpeg {{[-o|--output]}} {{path/to/file.jpg}}`

- Cattura un'immagine con dimensioni impostate:

`rpicam-jpeg {{[-o|--output]}} {{path/to/file.jpg}} --width {{1920}} --height {{1080}}`

- Cattura un'immagine con un'esposizione di 20 secondi e un guadagno del 150%:

`rpicam-jpeg {{[-o|--output]}} {{path/to/file.jpg}} --shutter 20000 --gain 1.5`
