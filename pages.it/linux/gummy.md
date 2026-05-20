# gummy

> Gestore di luminosità/temperatura dello schermo per Linux/X11.
> Maggiori informazioni: <https://github.com/Gitoffthelawn/gummy>.

- Imposta la temperatura dello schermo a 3000K:

`gummy {{[-t|--temperature]}} {{3000}}`

- Imposta la retroilluminazione dello schermo al 50%:

`gummy --backlight {{50}}`

- Imposta la luminosità dei pixel dello schermo al 45%:

`gummy {{[-b|--brightness]}} {{45}}`

- Aumenta la luminosità corrente dei pixel dello schermo del 10%:

`gummy {{[-b|--brightness]}} {{+10}}`

- Diminuisce la luminosità corrente dei pixel dello schermo del 10%:

`gummy {{[-b|--brightness]}} {{-10}}`

- Imposta la temperatura e la luminosità dei pixel per il secondo schermo:

`gummy {{[-s|--screen]}} {{1}} {{[-t|--temperature]}} {{3800}} {{[-b|--brightness]}} {{65}}`
