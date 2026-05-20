# eix

> Utilità per la ricerca di pacchetti Gentoo locali.
> Aggiorna la cache dei pacchetti locale usando `eix-update`.
> Maggiori informazioni: <https://wiki.gentoo.org/wiki/Eix>.

- Cerca un pacchetto:

`eix {{query}}`

- Cerca pacchetti installati:

`eix --installed {{query}}`

- Cerca nelle descrizioni dei pacchetti:

`eix --description "{{descrizione}}"`

- Cerca per licenza del pacchetto:

`eix --license {{licenza}}`

- Esclude i risultati dalla ricerca:

`eix --not --license {{licenza}}`
