# xrdb

> Database delle risorse del server X Window per sistemi Unix-like.
> Maggiori informazioni: <https://www.x.org/releases/current/doc/man/man1/xrdb.1.xhtml>.

- Avvia `xrdb` in modalità interattiva:

`xrdb`

- Carica valori (es. regole di stile) da un file di risorse:

`xrdb -load {{~/.Xresources}}`

- Interroga il database delle risorse e stampa i valori attualmente impostati:

`xrdb -query`
