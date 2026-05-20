# hyprpaper

> Utility per sfondi per Hyprland con la possibilità di cambiare dinamicamente gli sfondi.
> Controllata dal file di configurazione `~/.config/hypr/hyprpaper.conf`.
> Maggiori informazioni: <https://wiki.hypr.land/Hypr-Ecosystem/hyprpaper/>.

- Avvia il demone `hyprpaper`:

`hyprpaper`

- Cambia lo sfondo per un monitor specifico:

`hyprctl hyprpaper wallpaper "{{monitor}},{{path/to/image.png}}"`

- Cambia lo sfondo predefinito per tutti i monitor non specificati e imposta la sua modalità di adattamento:

`hyprctl hyprpaper wallpaper ",{{path/to/image.png}},{{contain|cover|tile|fill}}"`
