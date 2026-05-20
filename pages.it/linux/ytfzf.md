# ytfzf

> Trova e scarica video e musica. Scritto in shell POSIX.
> Vedi anche: `youtube-dl`, `yt-dlp`, `instaloader`.
> Maggiori informazioni: <https://manned.org/ytfzf>.

- Cerca video su YouTube con anteprime delle miniature:

`ytfzf {{[-t|--show-thumbnails]}} {{pattern_ricerca}}`

- Riproduci solo l'audio del primo elemento in un ciclo:

`ytfzf {{[-m|--audio-only]}} {{[-a|--auto-select]}} {{[-l|--loop]}} {{pattern_ricerca}}`

- Scarica un video dalla cronologia:

`ytfzf {{[-d|--download]}} --choose-from-history`

- Riproduci tutta la musica trovata in una ricerca:

`ytfzf {{[-m|--audio-only]}} {{[-A|--select-all]}} {{pattern_ricerca}}`

- Vedi i video di tendenza in un menu esterno:

`ytfzf --trending --ext-menu {{pattern_ricerca}}`

- Cerca su PeerTube invece di YouTube:

`ytfzf --peertube {{pattern_ricerca}}`
