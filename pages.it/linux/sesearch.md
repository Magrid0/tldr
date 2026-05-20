# sesearch

> Cerca le regole delle politiche SELinux.
> Parte del pacchetto `setools`.
> Vedi anche: `semodule`.
> Maggiori informazioni: <https://manned.org/sesearch>.

- Cerca tutte le regole di permesso:

`sesearch --allow`

- Cerca le regole relative a un tipo specifico:

`sesearch --allow {{[-t|--target]}} {{nome_tipo}}`

- Cerca le regole relative a un tipo sorgente specifico:

`sesearch --allow {{[-s|--source]}} {{tipo_sorgente}}`

- Cerca le regole che permettono una classe e un permesso specifici:

`sesearch --allow {{[-c|--class]}} {{nome_classe}} {{[-p|--perm]}} {{permesso}}`

- Cerca le regole con un tipo target e una classe specifici:

`sesearch --allow {{[-t|--target]}} {{nome_tipo}} {{[-c|--class]}} {{nome_classe}}`

- Mostra informazioni più dettagliate sulle regole corrispondenti:

`sesearch --allow {{[-t|--target]}} {{nome_tipo}} {{[-v|--verbose]}}`
