# rpicam-hello

> Visualizza un flusso live della fotocamera usando una fotocamera Raspberry Pi.
> Maggiori informazioni: <https://www.raspberrypi.com/documentation/computers/camera_software.html#rpicam-hello>.

- Mostra un'anteprima della fotocamera per un determinato periodo di tempo (in millisecondi):

`rpicam-hello {{[-t|--timeout]}} {{time}}`

- Ottimizza la configurazione per un particolare sensore della fotocamera:

`rpicam-hello --tuning-file {{/usr/share/libcamera/ipa/rpi/path/to/config.json}}`
