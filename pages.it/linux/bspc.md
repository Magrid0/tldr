# bspc

> Configura e controlla `bspwm`, gestendo nodi, desktop, monitor e altro.
> Vedi anche: `bspwm`.
> Maggiori informazioni: <https://github.com/baskerville/bspwm/blob/master/doc/bspwm.1.asciidoc>.

- Definisce due desktop virtuali:

`bspc monitor {{[-d|--reset-desktops]}} {{desktop_name1}} {{desktop_name2}}`

- Focalizza il desktop specificato:

`bspc desktop {{[-f|--focus]}} {{number}}`

- Chiude le finestre radicate nel nodo selezionato:

`bspc node {{[-c|--close]}}`

- Invia il nodo selezionato al desktop specificato:

`bspc node {{[-d|--to-desktop]}} {{number}}`

- Attiva/disattiva la modalità schermo intero per il nodo selezionato:

`bspc node {{[-t|--state]}} ~fullscreen`

- Imposta il valore di una specifica impostazione:

`bspc config {{setting_name}} {{value}}`
