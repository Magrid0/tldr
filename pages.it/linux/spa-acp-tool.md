# spa-acp-tool

> Esegue il debug del probing dei profili delle schede ALSA senza eseguire PipeWire.
> Maggiori informazioni: <https://docs.pipewire.org/page_man_spa-acp-tool_1.html>.

- Elenca tutti gli oggetti ALSA:

`spa-acp-tool {{[l|list]}}`

- Sonda una scheda ALSA specifica tramite ID:

`spa-acp-tool {{[c|card]}} {{id_scheda}}`

- Elenca i profili ALSA disponibili per una scheda:

`spa-acp-tool {{[lpr|list-profiles]}} {{id_scheda}}`

- Imposta il profilo ALSA attivo tramite ID:

`spa-acp-tool {{[spr|set-profile]}} {{id_profilo}}`

- Elenca i dispositivi disponibili per una scheda:

`spa-acp-tool {{[ld|list-devices]}} {{id_scheda}}`

- Ottiene il volume da un dispositivo:

`spa-acp-tool {{[gv|get-volume]}} {{id_dispositivo}}`

- Imposta il volume su un dispositivo:

`spa-acp-tool {{[v|set-volume]}} {{id_dispositivo}} {{livello_volume}}`

- Commuta lo stato di muto su un dispositivo:

`spa-acp-tool {{[m|toggle-mute]}} {{id_dispositivo}}`
