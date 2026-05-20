# hyprpicker

> Selettore di colore minimale per Wayland per compositori wlroots (es., Hyprland).
> Richiede una sessione Wayland. Per la copia automatica negli appunti, `wl-copy` deve essere installato.
> Maggiori informazioni: <https://wiki.hypr.land/Hypr-Ecosystem/hyprpicker/>.

- Seleziona un colore nel formato predefinito (hex):

`hyprpicker`

- Seleziona un colore e lo mostra in un formato specifico:

`hyprpicker {{[-f|--format]}} {{hex|rgb|hsl|hsv|cmyk}}`

- Copia il colore selezionato negli appunti:

`hyprpicker {{[-a|--autocopy]}}`

- Disabilita l'output colorato (mostra solo testo normale):

`hyprpicker {{[-n|--no-fancy]}}`

- Salva il colore selezionato in una variabile di shell:

`{{color}}=$(hyprpicker {{[-f|--format]}} {{hex}})`

- Mostra aiuto:

`hyprpicker {{[-h|--help]}}`
