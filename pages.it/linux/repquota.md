# repquota

> Mostra un riepilogo delle quote file esistenti per un filesystem.
> Maggiori informazioni: <https://manned.org/repquota>.

- Segnala le statistiche per tutte le quote in uso:

`sudo repquota {{[-a|--all]}}`

- Segnala le statistiche delle quote per tutti gli utenti, anche quelli che non stanno usando la loro quota:

`sudo repquota {{[-v|--verbose]}} {{filesystem}}`

- Segnala solo le quote per gli utenti:

`repquota {{[-u|--user]}} {{filesystem}}`

- Segnala solo le quote per i gruppi:

`sudo repquota {{[-g|--group]}} {{filesystem}}`

- Segnala la quota utilizzata e i limiti in un formato leggibile:

`sudo repquota {{[-s|--human-readable]}} {{filesystem}}`

- Segnala tutte le quote per utenti e gruppi in un formato leggibile:

`sudo repquota {{[-augs|--all --user --group --human-readable]}}`
