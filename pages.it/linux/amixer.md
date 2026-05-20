# amixer

> Mixer per il driver della scheda audio ALSA.
> Maggiori informazioni: <https://manned.org/amixer>.

- Aumenta il volume principale del 10%:

`amixer -D pulse sset Master {{10%+}}`

- Diminuisce il volume principale del 10%:

`amixer -D pulse sset Master {{10%-}}`
