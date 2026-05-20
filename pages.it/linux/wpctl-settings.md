# wpctl settings

> Gestisci le impostazioni di runtime di WirePlumber.
> Maggiori informazioni: <https://pipewire.pages.freedesktop.org/wireplumber/daemon/configuration/configuration_option_types.html>.

- Elenca tutte le impostazioni:

`wpctl settings`

- Visualizza il valore di un'impostazione specifica:

`wpctl settings {{id_impostazione}}`

- Imposta l'intero sistema per avere audio mono:

`wpctl settings node.features.audio.mono true`

- Imposta se la disconnessione degli altoparlanti metterà in pausa la riproduzione:

`wpctl settings linking.pause-playback {{true|false}}`
