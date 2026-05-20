# plasmashell

> Avvia e riavvia Plasma Desktop.
> Maggiori informazioni: <https://invent.kde.org/plasma/plasma-desktop>.

- Riavvia `plasmashell`:

`systemctl restart --user plasma-plasmashell`

- Riavvia `plasmashell` senza systemd:

`plasmashell --replace & disown`

- Mostra aiuto:

`plasmashell {{[-h|--help]}}`

- Mostra aiuto, incluse le opzioni Qt:

`plasmashell --help-all`
