# xdg-desktop-menu

> Installa o disinstalla voci di menu desktop.
> Maggiori informazioni: <https://manned.org/xdg-desktop-menu>.

- Installa un'applicazione nel sistema di menu desktop:

`xdg-desktop-menu install {{path/to/file.desktop}}`

- Installa un'applicazione nel sistema di menu desktop con il controllo del prefisso vendor disabilitato:

`xdg-desktop-menu install --novendor {{path/to/file.desktop}}`

- Disinstalla un'applicazione dal sistema di menu desktop:

`xdg-desktop-menu uninstall {{path/to/file.desktop}}`

- Forza un aggiornamento del sistema di menu desktop:

`xdg-desktop-menu forceupdate --mode {{user|system}}`
