# hyprsunset

> Un filtro per la luce blu per Hyprland.
> Opzionalmente configurato tramite `~/.config/hypr/hyprsunset.conf`.
> Maggiori informazioni: <https://wiki.hypr.land/Hypr-Ecosystem/hyprsunset/>.

- Avvia il servizio hyprsunset:

`hyprsunset`

- Avvia il servizio hyprsunset con una temperatura colore e una percentuale gamma specificate:

`hyprsunset {{[-t|--temperature]}} {{temperature}} {{[-g|--gamma]}} {{gamma}}`

- Regola la temperatura colore mentre il servizio hyprsunset è in esecuzione:

`hyprctl hyprsunset temperature {{temperature}}`

- Regola il gamma mentre il servizio hyprsunset è in esecuzione:

`hyprctl hyprsunset gamma {{gamma}}`

- Reimposta la temperatura colore a 6000K:

`hyprctl hyprsunset reset temperature`

- Reimposta il gamma al 100%:

`hyprctl hyprsunset reset gamma`
