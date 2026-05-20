# gio trash

> Sposta i file nel cestino.
> Utilizzato da GNOME per gestire il cestino.
> Maggiori informazioni: <https://manned.org/gio>.

- Sposta file specifici nel cestino:

`gio trash {{path/to/file_or_directory1 path/to/file_or_directory2 ...}}`

- Elenca gli elementi nel cestino:

`gio trash --list`

- Svuota il cestino:

`gio trash --empty`

- Ripristina un elemento specifico dal cestino usando il suo ID:

`gio trash trash://{{id}}`
