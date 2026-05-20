# i3-scrot

> Script wrapper per l'utility di screenshot `scrot` per il window manager i3.
> Il percorso di salvataggio predefinito è `~/Pictures` e può essere modificato in `~/.config/i3-scrot.conf`.
> Maggiori informazioni: <https://gitlab.manjaro.org/packages/extra/i3-scrot>.

- Cattura uno screenshot dell'intero schermo e lo salva nella directory predefinita:

`i3-scrot`

- Cattura uno screenshot della finestra attiva:

`i3-scrot --window`

- Cattura uno screenshot di una specifica selezione rettangolare:

`i3-scrot --select`

- Cattura uno screenshot dell'intero schermo e lo copia negli appunti:

`i3-scrot --desk-to-clipboard`

- Cattura uno screenshot della finestra attiva e lo copia negli appunti:

`i3-scrot --window-to-clipboard`

- Cattura uno screenshot di una selezione specifica e lo copia negli appunti:

`i3-scrot --select-to-clipboard`

- Cattura uno screenshot della finestra attiva dopo un ritardo di 5 secondi:

`i3-scrot --window {{5}}`
