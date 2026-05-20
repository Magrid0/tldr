# cliphist

> Gestisce la cronologia degli appunti per i compositor Wayland.
> Funziona con `wl-copy` e `wl-paste`.
> Maggiori informazioni: <https://github.com/sentriz/cliphist#usage>.

- Elenca le voci della cronologia degli appunti:

`cliphist list`

- Seleziona e copia una voce precedente degli appunti (utilizzando `fzf`):

`cliphist list | fzf | cliphist decode | wl-copy`

- Elimina tutte le voci memorizzate degli appunti:

`cliphist wipe`

- Elimina una voce specifica degli appunti tramite ID:

`cliphist delete {{id}}`

- Salva manualmente il contenuto corrente degli appunti:

`wl-paste | cliphist store`
