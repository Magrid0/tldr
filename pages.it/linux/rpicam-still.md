# rpicam-still

> Cattura e salva una foto usando una fotocamera Raspberry Pi con funzionalità legacy assenti in `rpicam-jpeg`.
> Maggiori informazioni: <https://www.raspberrypi.com/documentation/computers/camera_software.html#rpicam-still>.

- Cattura una foto con codifica diversa:

`rpicam-still {{[-e|--encoding]}} {{bmp|png|rgb|yuv420}} {{[-o|--output]}} {{path/to/file.[bmp|png|rgb|yuv420]}}`

- Cattura un'immagine raw:

`rpicam-still {{[-r|--raw]}} {{[-o|--output]}} {{path/to/file.jpg}}`

- Cattura un'immagine con esposizione di 100 secondi:

`rpicam-still {{[-o|--output]}} {{path/to/file.jpg}} --shutter 100000`
