# xmodmap

> Utilità per modificare i keymap e i mapping dei pulsanti del puntatore in X.
> Maggiori informazioni: <https://manned.org/xmodmap>.

- Scambia `<LeftClick>` e `<RightClick>` sul puntatore:

`xmodmap -e 'pointer = 3 2 1'`

- Ri Assegna un tasto della tastiera a un altro tasto:

`xmodmap -e 'keycode {{codice_tasto}} = {{nome_tasto}}'`

- Disabilita un tasto sulla tastiera:

`xmodmap -e 'keycode {{codice_tasto}} ='`

- Esegui tutte le espressioni xmodmap nel file specificato:

`xmodmap {{path/to/file}}`
