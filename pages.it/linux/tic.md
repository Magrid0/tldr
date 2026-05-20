# tic

> Compila terminfo e installa per ncurses.
> Maggiori informazioni: <https://manned.org/tic>.

- Compila e installa terminfo per un terminale:

`tic -xe {{terminale}} {{percorso/di/terminale.info}}`

- Controlla la presenza di errori nel file terminfo:

`tic -c {{percorso/di/terminale.info}}`

- Stampa le posizioni del database:

`tic -D`
