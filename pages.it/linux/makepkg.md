# makepkg

> Crea un pacchetto che può essere usato con `pacman`.
> Usa il file `PKGBUILD` nella directory corrente in modo predefinito.
> Maggiori informazioni: <https://manned.org/makepkg>.

- Crea un pacchetto:

`makepkg`

- Crea un pacchetto e installa le sue dipendenze:

`makepkg {{[-s|--syncdeps]}}`

- Crea un pacchetto, installa le sue dipendenze e poi lo installa nel sistema:

`makepkg {{[-si|--syncdeps --install]}}`

- Crea un pacchetto, ma salta il controllo degli hash dei sorgenti:

`makepkg --skipchecksums`

- Pulisce le directory di lavoro dopo una compilazione riuscita:

`makepkg {{[-c|--clean]}}`

- Verifica gli hash dei sorgenti:

`makepkg --verifysource`

- Genera e salva le informazioni sui sorgenti in `.SRCINFO`:

`makepkg --printsrcinfo > .SRCINFO`

- Scarica i sorgenti e installa solo le dipendenze di compilazione per un programma:

`makepkg {{[-so|--syncdeps --nobuild]}}`
