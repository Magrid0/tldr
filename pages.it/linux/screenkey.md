# screenkey

> Uno strumento per screencast per mostrare i tasti premuti.
> Maggiori informazioni: <https://www.thregr.org/wavexx/software/screenkey/>.

- Mostra i tasti che vengono premuti sullo schermo:

`screenkey`

- Mostra i tasti e i pulsanti del mouse che vengono premuti sullo schermo:

`screenkey {{[-M|--mouse]}}`

- Avvia il menu delle impostazioni di screenkey:

`screenkey --show-settings`

- Avvia screenkey in una posizione specifica:

`screenkey {{[-p|--position]}} {{top|center|bottom|fixed}}`

- Cambia il formato dei modificatori dei tasti mostrati sullo schermo:

`screenkey --mods-mode {{normal|emacs|mac|win|tux}}`

- Cambia l'aspetto di screenkey:

`screenkey --bg-color "{{#a1b2c3}}" {{[-f|--font]}} {{Hack}} --font-color {{yellow}} --opacity {{0.8}}`

- Trascina e seleziona una finestra sullo schermo per mostrare screenkey:

`screenkey {{[-p|--position]}} fixed {{[-g|--geometry]}} {{$(slop --nodecorations --format '%g')}}`
