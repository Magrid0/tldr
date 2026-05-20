# guix package

> Installa, aggiorna e rimuove pacchetti Guix o torna a configurazioni precedenti.
> Maggiori informazioni: <https://guix.gnu.org/manual/en/guix.html#Invoking-guix-package>.

- Installa un nuovo pacchetto:

`guix package {{[-i|--install]}} {{package}}`

- Rimuove un pacchetto:

`guix package {{[-r|--remove]}} {{package}}`

- Cerca nel database dei pacchetti un `regex`:

`guix package {{[-s|--search]}} "{{search_pattern}}"`

- Elenca i pacchetti installati:

`guix package {{[-I|--list-installed]}}`

- Elenca le generazioni:

`guix package {{[-l|--list-generations]}}`

- Torna alla generazione precedente:

`guix package --roll-back`
