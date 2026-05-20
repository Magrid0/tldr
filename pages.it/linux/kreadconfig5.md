# kreadconfig5

> Legge le voci KConfig per KDE Plasma.
> Maggiori informazioni: <https://userbase.kde.org/KDE_System_Administration/Configuration_Files>.

- Legge una chiave dalla configurazione globale:

`kreadconfig5 --group {{group_name}} --key {{key_name}}`

- Legge una chiave da un file di configurazione specifico:

`kreadconfig5 --file {{path/to/file}} --group {{group_name}} --key {{key_name}}`

- Controlla se systemd è usato per avviare la sessione Plasma:

`kreadconfig5 --file {{startkderc}} --group {{General}} --key {{systemdBoot}}`
