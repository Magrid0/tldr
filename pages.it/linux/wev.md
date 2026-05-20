# wev

> Stampa il contenuto degli eventi Wayland.
> Maggiori informazioni: <https://manned.org/wev>.

- Monitora tutti gli eventi Wayland che si verificano:

`wev`

- Stampa tutti gli eventi ricevuti da un'interfaccia Wayland specifica:

`wev -f {{wl_keyboard}}`

- Stampa solo eventi specifici ricevuti da un'interfaccia Wayland:

`wev -f {{wl_keyboard}}:{{key}}`

- Stampa tutto tranne gli eventi Wayland specificati:

`wev -F {{wl_keyboard}}:{{key}}`

- Scrivi la mappa dei tasti di `wl_keyboards` in un file:

`wev -M {{percorso/del/file}}`

- Stampa i globali Wayland:

`wev -g`
