# checkupdates

> Controlla gli aggiornamenti in sospeso in Arch Linux.
> Maggiori informazioni: <https://manned.org/checkupdates>.

- Sincronizza il database ed elenca gli aggiornamenti in sospeso:

`checkupdates`

- Elenca gli aggiornamenti in sospeso senza sincronizzare il database:

`checkupdates {{[-n|--nosync]}}`

- Mostra l'elenco degli aggiornamenti in sospeso se è diverso dall'ultima volta che questa opzione è stata utilizzata:

`checkupdates {{[-c|--change]}}`

- Elenca gli aggiornamenti in sospeso e scarica i pacchetti nella cache di `pacman` (`/var/cache/pacman/pkg`):

`checkupdates {{[-d|--download]}}`

- Elenca gli aggiornamenti in sospeso utilizzando un database `pacman` specifico:

`CHECKUPDATES_DB={{path/to/directory}} checkupdates`

- Mostra aiuto:

`checkupdates {{[-h|--help]}}`
