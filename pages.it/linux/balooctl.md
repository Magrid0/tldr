# balooctl

> Framework di indicizzazione e ricerca file per KDE Plasma.
> Maggiori informazioni: <https://wiki.archlinux.org/title/Baloo>.

- Mostra lo stato dell'indicizzatore:

`balooctl status`

- Abilita/disabilita l'indicizzatore file:

`balooctl {{enable|disable}}`

- Pulisce il database dell'indice:

`balooctl purge`

- Sospende l'indicizzatore file:

`balooctl suspend`

- Riprende l'indicizzatore file:

`balooctl resume`

- Mostra lo spazio su disco utilizzato da Baloo:

`balooctl indexSize`

- Controlla eventuali file non indicizzati e li indicizza:

`balooctl check`

- Mostra aiuto:

`balooctl {{[-h|--help]}}`
