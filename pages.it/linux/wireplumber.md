# wireplumber

> Un gestore di sessioni/politiche modulare per PipeWire e una libreria di alto livello basata su GObject che incapsula l'API di PipeWire.
> Vedi anche: `wpctl`, `pipewire`.
> Maggiori informazioni: <https://pipewire.pages.freedesktop.org/wireplumber/>.

- Fa partire WirePlumber con la sessione utente immediatamente (per sistemi systemd):

`systemctl --user --now enable wireplumber`

- Esegue WirePlumber, dopo che `pipewire` è stato avviato (per sistemi non systemd):

`wireplumber`

- Specifica un file di configurazione del contesto diverso:

`wireplumber --config-file {{percorso/del/file}}`

- Mostra aiuto:

`wireplumber --help`

- Mostra versione:

`wireplumber --version`
