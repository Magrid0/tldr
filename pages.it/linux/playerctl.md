# playerctl

> Controlla i lettori multimediali tramite MPRIS.
> Maggiori informazioni: <https://github.com/altdesktop/playerctl#using-the-cli>.

- Attiva/disattiva la riproduzione:

`playerctl play-pause`

- Passa alla traccia successiva:

`playerctl next`

- Torna alla traccia precedente:

`playerctl previous`

- Elenca tutti i lettori:

`playerctl {{[-l|--list-all]}}`

- Invia un comando a un lettore specifico:

`playerctl {{[-p|--player]}} {{nome_lettore}} {{play-pause|next|previous|...}}`

- Invia un comando a tutti i lettori:

`playerctl {{[-a|--all-players]}} {{play-pause|next|previous|...}}`

- Mostra i metadati della traccia corrente:

`playerctl metadata {{[-f|--format]}} "{{Now playing: \{\{artist\}\} - \{\{album\}\} - \{\{title\}\}}}"`
