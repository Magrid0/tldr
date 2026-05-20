# localectl

> Controlla le impostazioni della locale di sistema e della disposizione della tastiera.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/localectl.html>.

- Mostra le impostazioni correnti della locale di sistema e della mappa della tastiera:

`localectl`

- Elenca le locali disponibili:

`localectl list-locales`

- Imposta una variabile di locale di sistema:

`localectl set-locale {{LANG}}={{en_US.UTF-8}}`

- Elenca le mappe della tastiera disponibili:

`localectl list-keymaps`

- Imposta la mappa della tastiera di sistema per la console e X11:

`localectl set-keymap {{us}}`
