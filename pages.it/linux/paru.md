# paru

> Un helper AUR e wrapper di pacman.
> Vedi anche: `pacman`, `yay`.
> Maggiori informazioni: <https://github.com/Morganamilo/paru#examples>.

- Cerca e installa interattivamente un pacchetto:

`paru {{nome_pacchetto_o_termine_ricerca}}`

- Sincronizza e aggiorna tutti i pacchetti:

`paru`

- Aggiorna i pacchetti AUR:

`paru -Sua`

- Rimuovi un pacchetto installato, i suoi file di configurazione e le dipendenze:

`paru -Rns {{pacchetto}}`

- Ottieni informazioni su un pacchetto:

`paru -Si {{pacchetto}}`

- Scarica `PKGBUILD` e altri file sorgente del pacchetto dall'AUR o ABS:

`paru --getpkgbuild {{pacchetto}}`

- Mostra il file `PKGBUILD` di un pacchetto:

`paru --getpkgbuild --print {{pacchetto}}`
