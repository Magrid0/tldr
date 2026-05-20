# paclock

> Blocca/sblocca il database di libalpm (usato da `pacman`) per impedire o consentire operazioni simultanee di gestione pacchetti.
> Maggiori informazioni: <https://github.com/andrewgregory/pacutils/blob/master/doc/paclock.pod>.

- Blocca il database:

`sudo paclock`

- Scrivi il percorso del file di blocco su `stdout` (senza bloccare il database):

`paclock --print`

- Sblocca il database:

`sudo paclock --unlock`

- Mostra aiuto:

`paclock --help`

- Mostra versione:

`paclock --version`
