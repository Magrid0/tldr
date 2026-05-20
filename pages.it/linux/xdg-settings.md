# xdg-settings

> Gestisce le impostazioni degli ambienti desktop compatibili XDG.
> Maggiori informazioni: <https://portland.freedesktop.org/doc/xdg-settings.html>.

- Stampa il browser web predefinito:

`xdg-settings get default-web-browser`

- Imposta il browser web predefinito su Firefox:

`xdg-settings set default-web-browser {{firefox.desktop}}`

- Imposta il gestore dello schema URL mail predefinito su Evolution:

`xdg-settings set default-url-scheme-handler mailto {{evolution.desktop}}`

- Imposta il visualizzatore PDF predefinito:

`xdg-settings set {{pdf-viewer.desktop}}`

- Mostra aiuto:

`xdg-settings --help`
