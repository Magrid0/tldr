# wal-telegram

> Genera temi per Telegram basati sui colori generati da pywal/wal.
> Maggiori informazioni: <https://github.com/guillaumeboehm/wal-telegram>.

- Genera con la palette di wal e lo sfondo corrente (solo feh):

`wal-telegram`

- Genera con la palette di wal e un'immagine di sfondo specificata:

`wal-telegram --background={{percorso/dell/immagine}}`

- Genera con la palette di wal e uno sfondo colorato basato sulla palette:

`wal-telegram --tiled`

- Applica una sfocatura gaussiana all'immagine di sfondo:

`wal-telegram -g`

- Specifica una posizione per il tema generato (default è `$XDG_CACHE_HOME/wal-telegram` o `~/.cache/wal-telegram`):

`wal-telegram --destination={{percorso/della/destinazione}}`

- Riavvia l'app Telegram dopo la generazione:

`wal-telegram --restart`
