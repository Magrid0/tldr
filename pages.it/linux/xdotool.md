# xdotool

> Automatizza le azioni X11.
> Maggiori informazioni: <https://manned.org/xdotool>.

- Recupera l'ID della finestra X-Windows delle finestre di Firefox in esecuzione:

`xdotool search --onlyvisible --name firefox`

- Esegui un `<RightClick>` del mouse:

`xdotool click 3`

- Ottieni l'ID della finestra attualmente attiva:

`xdotool getactivewindow`

- Sposta il focus sulla finestra con un ID specifico:

`xdotool windowfocus --sync {{12345}}`

- Scrivi un messaggio, con un ritardo di 500ms per ogni lettera:

`xdotool type --delay 500 "{{Hello world}}"`

- Premi il tasto `<Enter>`:

`xdotool key KP_Enter`
