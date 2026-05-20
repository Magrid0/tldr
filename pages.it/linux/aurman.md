# aurman

> Utility di Arch Linux per costruire e installare pacchetti dall'Arch User Repository.
> Vedi anche: `pacman`.
> Maggiori informazioni: <https://github.com/polygamma/aurman#syntax>.

- Sincronizza e aggiorna tutti i pacchetti:

`aurman {{[-S|--sync]}} {{[-y|--refresh]}} {{[-u|--sysupgrade]}}`

- Sincronizza e aggiorna tutti i pacchetti senza mostrare modifiche dei file `PKGBUILD`:

`aurman {{[-S|--sync]}} {{[-y|--refresh]}} {{[-u|--sysupgrade]}} --noedit`

- Installa un nuovo pacchetto:

`aurman {{[-S|--sync]}} {{pacchetto}}`

- Installa un nuovo pacchetto senza mostrare modifiche dei file `PKGBUILD`:

`aurman {{[-S|--sync]}} --noedit {{pacchetto}}`

- Installa un nuovo pacchetto senza richiedere conferma:

`aurman {{[-S|--sync]}} --noedit --noconfirm {{pacchetto}}`

- Cerca nel database dei pacchetti una parola chiave nei repository ufficiali e AUR:

`aurman {{[-S|--sync]}} {{[-s|--search]}} {{parola_chiave}}`

- Rimuove un pacchetto e le sue dipendenze:

`aurman --remove --recursive --nosave {{pacchetto}}`

- Pulisce la cache dei pacchetti (usa due flag `--clean` per pulire tutti i pacchetti):

`aurman {{[-S|--sync]}} {{[-c|--clean]}}`
