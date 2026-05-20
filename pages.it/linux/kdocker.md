# kdocker

> Aggancia facilmente applicazioni alla system tray.
> Maggiori informazioni: <https://github.com/user-none/KDocker>.

- Mostra un cursore per inviare una finestra alla system tray premendo il pulsante sinistro del mouse (premere qualsiasi altro pulsante del mouse per annullare):

`kdocker`

- Apre un'applicazione e la invia alla system tray:

`kdocker {{application}}`

- Invia la finestra attiva alla system tray:

`kdocker -f`

- Mostra un cursore per inviare una finestra alla system tray con un'icona personalizzata premendo il pulsante sinistro del mouse:

`kdocker -i /{{path/to/icon}}`

- Apre un'applicazione, la invia alla system tray e se perde il focus, la minimizza:

`kdocker -l {{application}}`

- Mostra versione:

`kdocker --version`
