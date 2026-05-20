# pacstall

> Un gestore di pacchetti AUR per Ubuntu.
> Maggiori informazioni: <https://github.com/pacstall/pacstall>.

- Cerca nel database dei pacchetti un nome:

`pacstall {{[-S|--search]}} {{query}}`

- Installa un pacchetto:

`pacstall {{[-I|--install]}} {{pacchetto}}`

- Rimuovi un pacchetto:

`pacstall {{[-R|--remove]}} {{pacchetto}}`

- Aggiungi un repository al database (solo GitHub e GitLab sono supportati):

`pacstall {{[-A|--add-repo]}} {{posizione_repository_remoto}}`

- Aggiorna gli script di pacstall:

`pacstall {{[-U|--update]}}`

- Aggiorna tutti i pacchetti:

`pacstall {{[-Up|--upgrade]}}`

- Mostra informazioni su un pacchetto:

`pacstall {{[-Ci|--cache-info]}} {{pacchetto}}`

- Elenca tutti i pacchetti installati:

`pacstall {{[-L|--list]}}`
