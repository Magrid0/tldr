# trizen

> Utility di Arch Linux per costruire pacchetti dall'Arch User Repository (AUR).
> Maggiori informazioni: <https://github.com/trizen/trizen/blob/master/TRIZEN.md>.

- Sincronizza e aggiorna tutti i pacchetti AUR:

`trizen -Syua`

- Installa un nuovo pacchetto:

`trizen -S {{pacchetto}}`

- Rimuovi un pacchetto e le sue dipendenze:

`trizen -Rs {{pacchetto}}`

- Cerca nel database dei pacchetti una parola chiave:

`trizen -Ss {{parola_chiave}}`

- Mostra informazioni su un pacchetto:

`trizen -Si {{pacchetto}}`

- Elenca i pacchetti installati e le versioni:

`trizen -Qe`
