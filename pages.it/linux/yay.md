# yay

> Yet Another Yogurt: costruisce e installa pacchetti dall'Arch User Repository.
> Vedi anche: `pacman`.
> Maggiori informazioni: <https://github.com/Jguer/yay#first-use>.

- Cerca e installa interattivamente pacchetti dai repository e AUR:

`yay {{nome_pacchetto|termine_ricerca}}`

- Sincronizza e aggiorna tutti i pacchetti dai repository e AUR:

`yay`

- Installa un nuovo pacchetto dai repository e AUR senza chiedere conferma:

`yay -S {{pacchetto}} --noconfirm`

- Rimuovi un pacchetto installato e le sue dipendenze e file di configurazione:

`yay -Rns {{pacchetto}}`

- Cerca nel database dei pacchetti una parola chiave dai repository e AUR:

`yay -Ss {{parola_chiave}}`

- Rimuovi i pacchetti orfani (installati come dipendenze ma non richiesti da alcun pacchetto):

`yay -Yc`

- Pulisci la cache di `pacman` e `yay` (vecchie versioni dei pacchetti conservate per rollback e downgrade):

`yay -Scc`

- Mostra statistiche per i pacchetti installati e salute del sistema:

`yay -Ps`
