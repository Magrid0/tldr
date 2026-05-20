# xbacklight

> Utilità per regolare la luminosità dello schermo usando l'estensione RandR.
> Maggiori informazioni: <https://manned.org/xbacklight>.

- Ottieni la luminosità corrente dello schermo in percentuale:

`xbacklight`

- Imposta la luminosità dello schermo al 40%:

`xbacklight -set {{40}}`

- Aumenta la luminosità corrente del 25%:

`xbacklight -inc {{25}}`

- Diminuisci la luminosità corrente del 75%:

`xbacklight -dec {{75}}`

- Aumenta la luminosità al 100% in 60 secondi (valore in ms), usando 60 passi:

`xbacklight -set {{100}} -time {{60000}} -steps {{60}}`
