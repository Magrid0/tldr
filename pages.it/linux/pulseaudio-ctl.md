# pulseaudio-ctl

> Controlla il volume di PulseAudio.
> Maggiori informazioni: <https://github.com/graysky2/pulseaudio-ctl>.

- Aumenta il volume del 5%:

`pulseaudio-ctl up`

- Aumenta il volume di una quantità specifica:

`pulseaudio-ctl up {{quantità}}`

- Diminuisci il volume del 5%:

`pulseaudio-ctl down`

- Diminuisci il volume di una quantità specifica:

`pulseaudio-ctl down {{quantità}}`

- Imposta il volume a una percentuale specifica:

`pulseaudio-ctl set {{percentuale}}`

- Imposta il volume a una percentuale specifica se il volume corrente è maggiore del valore fornito:

`pulseaudio-ctl atmost {{percentuale}}`

- Attiva/disattiva l'audio muto:

`pulseaudio-ctl mute`

- Attiva/disattiva l'audio muto del microfono:

`pulseaudio-ctl mute-input`
