# vkpurge

> Elenca o rimuove le versioni del kernel vecchie lasciate da `xbps`.
> Gli argomenti `version` supportano glob shell.
> Maggiori informazioni: <https://man.voidlinux.org/vkpurge.8>.

- Elenca tutte le versioni del kernel rimovibili (o quelle corrispondenti a `version` se l'argomento è specificato):

`vkpurge list {{versione}}`

- Rimuove tutti i kernel inutilizzati:

`vkpurge rm all`

- Rimuove le versioni del kernel corrispondenti a `version`:

`vkpurge rm {{versione}}`
