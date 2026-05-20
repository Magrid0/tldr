# fuzzel

> Un lanciatore di applicazioni e cercatore fuzzy nativo Wayland, ispirato a `rofi` e `dmenu`.
> Maggiori informazioni: <https://codeberg.org/dnkl/fuzzel>.

- Esegue applicazioni:

`fuzzel`

- Esegue `fuzzel` in modalità dmenu:

`fuzzel {{[-d|--dmenu]}}`

- Mostra un menu con l'output del comando `ls`:

`{{ls}} | fuzzel {{[-d|--dmenu]}}`

- Mostra un menu con elementi personalizzati separati da una nuova riga (`\n`):

`echo -e "{{red}}\n{{green}}\n{{blue}}" | fuzzel {{[-d|--dmenu]}}`

- Permette all'utente di scegliere tra più elementi e salva quello selezionato in un file:

`echo -e "{{red}}\n{{green}}\n{{blue}}" | fuzzel {{[-d|--dmenu]}} > {{color.txt}}`

- Resetta il conteggio di utilizzo delle app (directory cache predefinita: `$XDG_CACHE_HOME/fuzzel`):

`rm {{[-v|--verbose]}} $HOME/.cache/fuzzel`

- Avvia `fuzzel` su un monitor specifico, vedi `wlr-randr` o `swaymsg --type get_outputs`:

`fuzzel {{[-o|--output]}} "{{DP-1}}"`

- Utilizza `fuzzel` per fare una ricerca online:

`fuzzel {{[-d|--dmenu]}} {{[-l|--lines]}} 0 --placeholder "{{Type your search}}" | sed 's/^/\"/g;s/$/\"/g' | xargs firefox --search`
