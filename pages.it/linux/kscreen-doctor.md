# kscreen-doctor

> Modifica e gestisce la configurazione dello schermo.
> Maggiori informazioni: <https://invent.kde.org/plasma/libkscreen>.

- Mostra le informazioni sulle uscite dello schermo:

`kscreen-doctor {{[-o|--outputs]}}`

- Imposta la rotazione di un'uscita dello schermo con ID 1 verso destra:

`kscreen-doctor output.1.rotation.right`

- Imposta la scala di un'uscita dello schermo con ID `HDMI-2` a 2 (200%):

`kscreen-doctor output.HDMI-2.scale.2`

- Abilita uno schermo HDMI specifico:

`kscreen-doctor output.{{HDMI-A-1}}.enable`

- Disabilita uno schermo DisplayPort specifico:

`kscreen-doctor output.{{DP-2}}.disable`

- Imposta uno schermo come schermo principale:

`kscreen-doctor output.{{HDMI-A-1}}.primary`

- Mostra aiuto:

`kscreen-doctor {{[-h|--help]}}`
