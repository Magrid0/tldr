# vcgencmd

> Stampa informazioni di sistema per un Raspberry Pi.
> Maggiori informazioni: <https://www.raspberrypi.com/documentation/computers/os.html#vcgencmd>.

- Elenca tutti i comandi disponibili:

`vcgencmd commands`

- Stampa la temperatura corrente della CPU:

`vcgencmd measure_temp`

- Stampa la tensione corrente:

`vcgencmd measure_volts`

- Stampa lo stato di throttling del sistema come pattern di bit:

`vcgencmd get_throttled`

- Stampa la configurazione del bootloader (disponibile solo sui modelli Raspberry Pi 4):

`vcgencmd bootloader_config`

- Mostra aiuto:

`vcgencmd --help`
