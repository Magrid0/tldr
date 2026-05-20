# snap

> Gestisce i pacchetti software autonomi "snap".
> Simile a ciò che `apt` è per i `.deb`.
> Maggiori informazioni: <https://manned.org/snap>.

- Cerca un pacchetto:

`snap find {{ricerca}}`

- Installa un pacchetto:

`snap install {{pacchetto}}`

- Aggiorna un pacchetto:

`snap refresh {{pacchetto}}`

- Aggiorna un pacchetto a un altro canale (track, risk o branch):

`snap refresh {{pacchetto}} --channel={{canale}}`

- Aggiorna tutti i pacchetti:

`snap refresh`

- Mostra informazioni di base sul software snap installato:

`snap list`

- Disinstalla un pacchetto:

`snap remove {{pacchetto}}`

- Controlla le modifiche recenti di snap nel sistema:

`snap changes`
