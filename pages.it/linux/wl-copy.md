# wl-copy

> Cancella e copia negli appunti di Wayland.
> Vedi anche: `wl-paste`, `xclip`.
> Maggiori informazioni: <https://github.com/bugaevc/wl-clipboard>.

- Copia il testo negli appunti:

`wl-copy "{{testo}}"`

- Invia l'output del comando (`ls`) agli appunti:

`{{ls}} | wl-copy`

- Copia per un solo incolla e poi cancella:

`wl-copy --paste-once "{{testo}}"`

- Copia un'immagine:

`wl-copy < {{percorso/dell/immagine}}`

- Cancella gli appunti:

`wl-copy --clear`
