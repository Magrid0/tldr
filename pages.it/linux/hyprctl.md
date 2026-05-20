# hyprctl

> Controlla parti del compositore Wayland Hyprland.
> Maggiori informazioni: <https://wiki.hypr.land/Configuring/Using-hyprctl/>.

- Ricarica la configurazione di Hyprland:

`hyprctl reload`

- Restituisce il nome della finestra attiva:

`hyprctl activewindow`

- Elenca tutti i dispositivi di input connessi:

`hyprctl devices`

- Elenca tutte le uscite con le rispettive proprietà:

`hyprctl workspaces`

- Chiama un dispatcher:

`hyprctl dispatch {{dispatcher}}`

- Imposta dinamicamente una parola chiave di configurazione:

`hyprctl keyword {{keyword}} {{value}}`

- Mostra versione:

`hyprctl version`
