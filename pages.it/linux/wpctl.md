# wpctl

> Gestisci WirePlumber, un gestore di sessioni e politiche per PipeWire.
> Nota: Puoi usare il nome speciale `@DEFAULT_SINK@` al posto di `id` per operare sul sink predefinito.
> Vedi anche: `pw-cli`.
> Maggiori informazioni: <https://pipewire.pages.freedesktop.org/wireplumber/>.

- Elenca tutti gli oggetti gestiti da WirePlumber:

`wpctl status`

- Stampa tutte le proprietà di un oggetto:

`wpctl inspect {{id}}`

- Imposta un oggetto come predefinito nel suo gruppo:

`wpctl set-default {{id}}`

- Ottieni il volume di un sink:

`wpctl get-volume {{id}}`

- Imposta il volume di un sink a `n` percento:

`wpctl set-volume {{id}} {{n}}%`

- Aumenta/Riduci il volume di un sink di `n` percento:

`wpctl set-volume {{id}} {{n}}%{{+|-}}`

- Aumenta il volume di un sink di `n` percento ma limita il volume sotto il 100%:

`wpctl set-volume {{[-l|--limit]}} 1 {{id}} {{n}}%-`

- Muta/Stumuta il sink o sorgente audio predefinito (1 muto, 0 non muto):

`wpctl set-mute @DEFAULT_{{SINK|SOURCE}}@ {{1|0|toggle}}`
