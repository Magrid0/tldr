# auracle

> Interagisce con l'Arch User Repository (AUR) di Arch Linux.
> Maggiori informazioni: <https://github.com/falconindy/auracle/blob/master/man/auracle.1.pod>.

- Mostra i pacchetti AUR che corrispondono a un `regex`:

`auracle search '{{regex}}'`

- Mostra informazioni su uno o più pacchetti AUR:

`auracle info {{pacchetto1 pacchetto2 ...}}`

- Mostra il file `PKGBUILD` (informazioni di build) di uno o più pacchetti AUR:

`auracle show {{pacchetto1 pacchetto2 ...}}`

- Mostra gli aggiornamenti per i pacchetti AUR installati:

`auracle outdated`
