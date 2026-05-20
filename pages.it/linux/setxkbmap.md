# setxkbmap

> Imposta la tastiera usando l'X Keyboard Extension.
> Maggiori informazioni: <https://manned.org/setxkbmap>.

- Imposta la tastiera in francese AZERTY:

`setxkbmap {{fr}}`

- Imposta più layout di tastiera, le loro varianti e l'opzione di commutazione:

`setxkbmap -layout {{us,de}} -variant {{,qwerty}} -option '{{grp:alt_caps_toggle}}'`

- Elenca tutti i layout:

`localectl list-x11-keymap-layouts`

- Elenca le varianti per il layout:

`localectl list-x11-keymap-variants {{de}}`

- Elenca le opzioni di commutazione disponibili:

`localectl list-x11-keymap-options | grep grp:`

- Mostra aiuto:

`setxkbmap -help`
