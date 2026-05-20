# rpicam-raw

> Cattura un video raw su una fotocamera Raspberry Pi.
> Maggiori informazioni: <https://www.raspberrypi.com/documentation/computers/camera_software.html#rpicam-raw>.

- Cattura un video per una durata specifica in secondi:

`rpicam-raw {{[-t|--timeout]}} {{2000}} {{[-o|--output]}} {{path/to/file.raw}}`

- Cambia le dimensioni del video e il framerate:

`rpicam-raw {{[-t|--timeout]}} {{5000}} --width {{4056}} --height {{3040}} {{[-o|--output]}} {{path/to/file.raw}} --framerate {{8}}`
