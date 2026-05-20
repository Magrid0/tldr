# maim

> Utility per screenshot.
> Maggiori informazioni: <https://manned.org/maim>.

- Cattura uno screenshot e lo salva nel percorso indicato:

`maim {{path/to/screenshot.png}}`

- Cattura uno screenshot dell'area selezionata:

`maim {{[-s|--select]}} {{path/to/screenshot.png}}`

- Cattura uno screenshot dell'area selezionata e lo salva negli appunti (richiede `xclip`):

`maim {{[-s|--select]}} | xclip {{[-se|-selection]}} {{[c|clipboard]}} {{[-t|-target]}} image/png`

- Cattura uno screenshot della finestra attiva corrente (richiede `xdotool`):

`maim {{[-i|--window]}} $(xdotool getactivewindow) {{path/to/screenshot.png}}`
