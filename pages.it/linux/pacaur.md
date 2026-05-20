# pacaur

> Un'utilità per Arch Linux per compilare e installare pacchetti dall'Arch User Repository.
> Maggiori informazioni: <https://github.com/rmarquis/pacaur#name>.

- Sincronizza e aggiorna tutti i pacchetti (include AUR):

`pacaur -Syu`

- Sincronizza e aggiorna solo pacchetti AUR:

`pacaur -Syua`

- Installa un nuovo pacchetto (include AUR):

`pacaur -S {{pacchetto}}`

- Rimuovi un pacchetto e le sue dipendenze (include pacchetti AUR):

`pacaur -Rs {{pacchetto}}`

- Cerca nel database dei pacchetti una parola chiave (include AUR):

`pacaur -Ss {{parola_chiave}}`

- Elenca tutti i pacchetti attualmente installati (include pacchetti AUR):

`pacaur -Qs`
