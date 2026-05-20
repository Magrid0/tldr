# xrandr

> Imposta dimensione, orientamento e/o riflessione degli output per uno schermo.
> Maggiori informazioni: <https://www.x.org/releases/current/doc/man/man1/xrandr.1.xhtml>.

- Mostra lo stato corrente del sistema (schermi noti, risoluzioni, ...):

`xrandr {{[-q|--query]}}`

- Disabilita gli output disconnessi e abilita quelli connessi con impostazioni predefinite:

`xrandr --auto`

- Cambia la risoluzione e la frequenza di aggiornamento di DisplayPort 1 a 1920x1080, 60Hz:

`xrandr --output DP1 --mode 1920x1080 {{[-r|--rate]}} 60`

- Imposta la risoluzione di HDMI2 a 1280x1024 e posizionalo a destra di DP1:

`xrandr --output HDMI2 --mode 1280x1024 --right-of DP1`

- Disabilita l'output VGA1:

`xrandr --output VGA1 --off`

- Imposta la luminosità per LVDS1 al 50%:

`xrandr --output LVDS1 --brightness 0.5`

- Mostra lo stato corrente di qualsiasi server X:

`xrandr {{[-d|--display]}} :{{0}} {{[-q|--query]}}`
