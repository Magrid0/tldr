# systemctl list-paths

> Elenca le unità di percorso attualmente in memoria, ordinate per percorso.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemctl.html#list-paths%20PATTERN%E2%80%A6>.

- Mostra tutte le unità di percorso attualmente in memoria:

`systemctl list-paths`

- Elenca le unità di percorso che corrispondono a un pattern wildcard specifico, ad esempio `shell-globbing`:

`systemctl list-paths {{pattern}}`

- Elenca le unità di percorso che corrispondono a più pattern:

`systemctl list-paths {{pattern_1 pattern_2 ...}}`

- Mostra tutte le unità di percorso, incluse quelle inattive:

`systemctl list-paths {{[-a|--all]}}`

- Filtra le unità di percorso per stato:

`systemctl list-paths --state {{stato}}`

- Mostra anche i tipi di unità nell'output:

`systemctl list-paths --show-types`
