# cdrecord

> Registra dati su CD o DVD.
> Alcune invocazioni di cdrecord possono causare azioni distruttive, come cancellare tutti i dati su un disco.
> Maggiori informazioni: <https://manned.org/cdrecord>.

- Mostra le unità ottiche disponibili per `cdrecord`:

`cdrecord --devices`

- Registra ("masterizza") un disco solo audio:

`cdrecord dev={{/dev/optical_drive}} -audio {{track*.cdaudio}}`

- Masterizza un file su un disco, espellendo il disco al termine (alcuni registratori lo richiedono):

`cdrecord -eject dev={{/dev/optical_drive}} -data {{file.iso}}`

- Masterizza un file sul disco in un'unità ottica, scrivendo potenzialmente su più dischi in successione:

`cdrecord -tao dev={{/dev/optical_drive}} -data {{file.iso}}`
