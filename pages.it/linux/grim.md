# grim

> Acquisisce immagini (screenshot) da un compositor Wayland.
> Maggiori informazioni: <https://sr.ht/~emersion/grim/>.

- Acquisisce uno screenshot di tutte le uscite:

`grim`

- Acquisisce uno screenshot di un'uscita specifica:

`grim -o {{path/to/output_file}}`

- Acquisisce uno screenshot di un'area specifica:

`grim -g "{{x_position}},{{y_position}} {{width}}x{{height}}"`

- Seleziona un'area specifica e ne acquisisce uno screenshot (usando slurp):

`grim -g "{{$(slurp)}}"`

- Usa un nome file personalizzato:

`grim "{{path/to/file.png}}"`

- Acquisisce uno screenshot e lo copia negli appunti:

`grim - | {{clipboard_manager}}`
