# wofi

> Un lanciatore di applicazioni per compositor Wayland basati su wlroots, simile a `rofi` e `dmenu`.
> Maggiori informazioni: <https://manned.org/wofi>.

- Mostra la lista delle app:

`wofi {{[-S|--show]}} drun`

- Mostra la lista di tutti i comandi:

`wofi {{[-S|--show]}} run`

- Invia una lista di elementi a `stdin` e stampa l'elemento selezionato su `stdout`:

`printf "{{Scelta1\nScelta2\nScelta3}}" | wofi {{[-d|--dmenu]}}`
