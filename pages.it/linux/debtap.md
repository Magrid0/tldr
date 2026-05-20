# debtap

> Converte pacchetti Debian in pacchetti Arch Linux.
> Vedi anche: `pacman-upgrade`.
> Maggiori informazioni: <https://github.com/helixarch/debtap#available-options>.

- Aggiorna il database debtap (prima del primo utilizzo):

`sudo debtap {{[-u|--update]}}`

- Converte il pacchetto specificato:

`debtap {{path/to/package.deb}}`

- Converte il pacchetto specificato saltando tutte le domande, tranne la modifica dei file di metadati:

`debtap {{[-q|--quiet]}} {{path/to/package.deb}}`

- Genera un file PKGBUILD:

`debtap {{[-p|--pkgbuild]}} {{path/to/package.deb}}`
