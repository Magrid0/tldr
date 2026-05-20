# ptyxis

> Un terminale orientato ai container per GNOME.
> Maggiori informazioni: <https://gitlab.gnome.org/chergert/ptyxis#basic-usage--command-line-options>.

- Apre una nuova finestra di Ptyxis:

`ptyxis --new-window`

- Esegue un comando specifico in una nuova finestra di terminale:

`ptyxis {{[-x|--execute]}} {{comando}}`

- Apre una nuova scheda nell'ultima finestra aperta:

`ptyxis --tab`

- Imposta il titolo per una nuova scheda:

`ptyxis --tab {{[-T|--title]}} {{titolo}}`

- Specifica la directory di lavoro per una nuova scheda, finestra o esecuzione comando:

`ptyxis {{[-d|--working-directory]}} {{percorso/directory}} --tab`
