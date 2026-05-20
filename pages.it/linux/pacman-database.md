# pacman --database

> Opera sul database dei pacchetti di Arch Linux.
> Modifica alcuni attributi dei pacchetti installati.
> Vedi anche: `pacman`.
> Maggiori informazioni: <https://manned.org/pacman.8>.

- Segna un pacchetto come installato implicitamente:

`sudo pacman -D --asdeps {{pacchetto}}`

- Segna un pacchetto come installato esplicitamente:

`sudo pacman -D --asexplicit {{pacchetto}}`

- Controlla che tutte le dipendenze dei pacchetti siano installate:

`pacman -Dk`

- Controlla il [D]atabase di sincronizzazione per assicurarsi che tutte le dipendenze specificate dei pacchetti scaricabili siano disponibili:

`pacman -Dkk`

- Controlla e mostra in modalità [q]uieta (vengono mostrati solo i messaggi di errore):

`pacman -Dkq`

- Mostra [h]elp:

`pacman -Dh`
