# startx

> Un front-end a `xinit` che fornisce una bella interfaccia utente per eseguire una singola sessione del X Window System.
> Maggiori informazioni: <https://www.x.org/releases/X11R7.6/doc/man/man1/startx.1.xhtml>.

- Avvia una sessione X:

`startx`

- Avvia una sessione X con un valore di profondità predefinito:

`startx -- -depth {{valore}}`

- Avvia una sessione X con un valore dpi predefinito:

`startx -- -dpi {{valore}}`

- Sovrascrive le impostazioni nel file `.xinitrc` e avvia una nuova sessione X:

`startx /{{percorso/del/window_manager_o_desktop_environment}}`
