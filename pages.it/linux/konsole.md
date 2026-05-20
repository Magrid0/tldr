# konsole

> Emulatore di terminale di KDE.
> Maggiori informazioni: <https://docs.kde.org/stable_kf6/en/konsole/konsole/command-line-options.html>.

- Apre il terminale in una directory specifica:

`konsole --workdir {{path/to/directory}}`

- Esegue un comando specifico e non chiude la finestra dopo l'uscita:

`konsole --noclose -e "{{command}}"`

- Apre una nuova scheda:

`konsole --new-tab`

- Apre il terminale in background e lo porta in primo piano quando si preme `<Ctrl Shift F12>`:

`konsole --background-mode`
