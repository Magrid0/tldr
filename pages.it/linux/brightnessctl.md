# brightnessctl

> Utility per leggere e controllare la luminosità del dispositivo per sistemi operativi Linux.
> Maggiori informazioni: <https://github.com/Hummer12007/brightnessctl#usage>.

- Elenca i dispositivi con luminosità modificabile:

`brightnessctl {{[-l|--list]}}`

- Stampa la luminosità attuale del dispositivo predefinito:

`brightnessctl {{[g|get]}}`

- Stampa la luminosità attuale di un dispositivo specifico (può essere un carattere jolly):

`brightnessctl {{[g|get]}} {{[-d|--device]}} '{{device_name}}'`

- Imposta la luminosità a una percentuale specificata:

`brightnessctl {{[s|set]}} {{50}}%`

- Aumenta la luminosità di una percentuale specificata:

`brightnessctl {{[s|set]}} +{{10}}%`

- Riduce la luminosità di una percentuale specificata:

`brightnessctl {{[s|set]}} {{10}}%-`
