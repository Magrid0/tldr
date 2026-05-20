# yaourt

> Utilità Arch Linux per costruire pacchetti dall'Arch User Repository.
> Maggiori informazioni: <https://archlinux.fr/yaourt-en>.

- Sincronizza e aggiorna tutti i pacchetti (inclusi AUR):

`yaourt -Syua`

- Installa un nuovo pacchetto (include AUR):

`yaourt -S {{pacchetto}}`

- Rimuovi un pacchetto e le sue dipendenze (include pacchetti AUR):

`yaourt -Rs {{pacchetto}}`

- Cerca nel database dei pacchetti una parola chiave (incluso AUR):

`yaourt -Ss {{query}}`

- Elenca i pacchetti installati, versioni e repository (i pacchetti AUR saranno elencati sotto il nome del repository `local`):

`yaourt -Q`
