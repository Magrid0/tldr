# ddcutil

> Controlla le impostazioni dei display collegati tramite DDC/CI.
> This command requires the kernel module `i2c-dev` to be loaded.
> Vedi anche: `modprobe`.
> Maggiori informazioni: <https://www.ddcutil.com/commands/>.

- Elenca tutti i display compatibili:

`ddcutil {{[det|detect]}}`

- Interroga il primo display compatibile per le capacità:

`ddcutil {{[cap|capabilities]}}`

- Cambia la luminosità (opzione `10`) del display 1 al 50%:

`ddcutil {{[-d|--display]}} 1 {{[set|setvcp]}} 10 50`

- Aumenta il contrasto (opzione `12`) del display 1 del 5%:

`ddcutil {{[-d|--display]}} 1 {{[set|setvcp]}} 12 + 5`

- Cambia la sorgente del display (opzione `60`):

`ddcutil {{[-d|--display]}} {{1}} {{[set|setvcp]}} 60 0x{{0f}}`

- Legge le impostazioni del display 1:

`ddcutil {{[-d|--display]}} 1 {{[get|getvcp]}} ALL`
