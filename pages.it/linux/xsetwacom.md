# xsetwacom

> Modifica le impostazioni per tavolette Wacom a runtime.
> Maggiori informazioni: <https://manned.org/xsetwacom>.

- Elenca tutti i dispositivi Wacom disponibili. Il nome del dispositivo è nella prima colonna:

`xsetwacom list`

- Imposta l'area Wacom su uno schermo specifico. Ottieni il nome dello schermo con `xrandr`:

`xsetwacom set "{{nome_dispositivo}}" MapToOutput {{schermo}}`

- Imposta la modalità su relativa (come un mouse) o assoluta (come una penna):

`xsetwacom set "{{nome_dispositivo}}" Mode "{{Relative|Absolute}}"`

- Ruota l'input (utile per tablet-PC quando si ruota lo schermo) di 0|90|180|270 gradi dalla rotazione "naturale":

`xsetwacom set "{{nome_dispositivo}}" Rotate {{none|half|cw|ccw}}`

- Imposta il pulsante per funzionare solo quando la punta della penna tocca la tavoletta:

`xsetwacom set "{{nome_dispositivo}}" TabletPCButton "on"`
