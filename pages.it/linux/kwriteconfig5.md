# kwriteconfig5

> Scrive voci KConfig per KDE Plasma.
> Maggiori informazioni: <https://userbase.kde.org/KDE_System_Administration/Configuration_Files>.

- Imposta una chiave di configurazione globale:

`kwriteconfig5 --group {{group_name}} --key {{key}} {{value}}`

- Imposta una chiave in un file di configurazione specifico:

`kwriteconfig5 --file {{path/to/file}} --group {{group_name}} --key {{key}} {{value}}`

- Elimina una chiave:

`kwriteconfig5 --group {{group_name}} --key {{key}} --delete`

- Usa systemd per avviare la sessione Plasma quando disponibile:

`kwriteconfig5 --file {{startkderc}} --group {{General}} --key {{systemdBoot}} {{true}}`

- Nasconde la barra del titolo quando una finestra è massimizzata (come Ubuntu):

`kwriteconfig5 --file {{~/.config/kwinrc}} --group {{Windows}} --key {{BorderlessMaximizedWindows}} {{true}}`

- Configura KRunner per aprirsi con il tasto Meta (Comando/Windows) globale:

`kwriteconfig5 --file {{~/.config/kwinrc}} --group {{ModifierOnlyShortcuts}} --key {{Meta}} "{{org.kde.kglobalaccel,/component/krunner_desktop,org.kde.kglobalaccel.Component,invokeShortcut,_launch}}"`

- Mostra aiuto:

`kwriteconfig5 --help`
