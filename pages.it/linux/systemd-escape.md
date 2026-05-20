# systemd-escape

> Escapa stringhe per l'uso nei nomi di unità systemd.
> Maggiori informazioni: <https://www.freedesktop.org/software/systemd/man/latest/systemd-escape.html>.

- Escapa il testo indicato:

`systemd-escape {{testo}}`

- Inverte il processo di escaping:

`systemd-escape {{[-u|--unescape]}} {{testo}}`

- Tratta il testo indicato come un percorso:

`systemd-escape {{[-p|--path]}} {{testo}}`

- Aggiunge il suffisso indicato al testo escapato:

`systemd-escape --suffix {{suffisso}} {{testo}}`

- Utilizza un template e vi inietta il testo escapato:

`systemd-escape --template {{template}} {{testo}}`
